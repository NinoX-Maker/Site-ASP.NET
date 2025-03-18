# Site-ASP.NET
<%@ Page Language="C#" AutoEventWireup="true" CodeBehind="WebForm1.aspx.cs" Inherits="REAL_site.WebForm1" %>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <asp:Label ID="Emaillabel" runat="server" Text="E-mail"></asp:Label>
        <br />
        <asp:textbox ID="EmailTextBox" runat="server" Width="173px"></asp:textbox>
        <br />
        <asp:Label ID="Senhalabel" runat="server" Text="Senha"></asp:Label>
        <br />
        <asp:textbox ID="SenhaTextbox1" runat="server" Width="73px"></asp:textbox>
        <br />
    </form>
</body>
</html>
