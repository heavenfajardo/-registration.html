# -registration.html
HTML Forms (with html exercise)

<!DOCTYPE html>
<html>

<body>

<form action="http://webdevfoundations.net/scripts/mydemo.asp" method="post">

First name
<input type="text" name="First name" maxlength="20">

Middle name
<input type="text" name="Middle name" maxlenght="20">

Last name
<input type="text" name="Last name"  maxlenght="20">

<br>
 
<input type="radio" name="gender" value="male"> Male<br>
<input type="radio" name="gender" value="female"> Female<br>
<input type="radio" name="gender" value="other"> Other <br>

<label for="email">Enter your email:</label>
<input type="email" id="email" maxlenght="15">
<br>
<textarea rows="10" cols="30">
Comment your Home Address Here in the Textbox
</textarea>
<br>
<input type="checkbox" name="Computer games" maxlenght="10"> 
<label for ="Computer games"> Computer games </label>
<br>
<input type="checkbox" name="Playing instruments" maxlenght="10">
<label for="Playing instruments"> Playing instruments </label>
<br>
<input type="checkbox" name="Cooking" maxlenght="10">Cooking
<br>
<input type="checkbox" name="Drawing" maxlenght="10">Drawing
</br>

<select>

<label> Your Favorite color</label>

<option value="Choose">Choose</option>

<option value="Red">Red</option>

<option value="Blue">Blue</option>

<option value="Green">Green</option>

<option value="Black">Black</option>

<option value="White">White</option>

</select>

</br>

</br>

<textarea rows="10" cols="30">
Say Something About Yourself
</textarea>
</br>

</br>

<input type="clear" name="clear" maxlenght="10">
<br>
<input type="submit" name="submit" maxlenght="10">
<br>
<input type="reset" value="clear" maxlenght="20">
</form>

</body>

</html>
