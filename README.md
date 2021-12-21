<html>
<head>
<title>Заголовок документа
<style>
.reg
{
width: 30%;
}
.reg table tr td
{
font-size: 10px;
}
.reg-btn
{
padding:5px 15px;
background:#ccc;
border:0 none;
cursor:pointer;
-webkit-border-radius: 5px;
border-radius: 5px;
}
</style>
</title>
</head>
<body>
<form >
<div class="reg">
<table>
<tr>
<td> Email</td>
<td> Пароль </td>
<td> Подтверждение пароля </td>

</tr>
<tr>
<td> <input type="email" required="required" placeholder="email" > <label></label> </td>
<td> <input type="password" required="required" placeholder="password" > </td>
<td> <input type="password" required="required" placeholder="repeat password" > </td>

</tr>
<tr>
<td> Ник</td>
<td> Телефон </td>
<td> Дата рождения </td>

</tr>
<tr>
<td> <input type="text" required="required" placeholder="login" > </td>
<td> <input type="tel" required="required" placeholder="+7 800 555 35 35" > </td>
<td> <input type="date" required="required" placeholder="01.01.2001" > </td>

</tr>
<tr>
<td> Фамилия</td>
<td> Имя </td>
<td> Отчество </td>

</tr>
<tr>
<td> <input type="text" required="required" placeholder="Фамилия" > </td>
<td> <input type="text" required="required" placeholder="Имя" > </td>
<td> <input type="text" required="required" placeholder="Отчество" > </td>

</tr>
<tr>
<td>
Пол
</td>
</tr>
<tr>
<td>
<input type="radio" id="contactChoice1" value="Мужской" checked>
<label for="contactChoice1">Мужской</label>
<input type="radio" id="contactChoice1" value="Женский">
<label for="contactChoice1">Женский</label>
</td>
</tr>
<tr>
<td> </td>
<td> </td>
<td> <input class="reg-btn" type="submit" value="Зарегистрироваться"> </td>
</tr>
</table>
</div>

</body>
</html>
