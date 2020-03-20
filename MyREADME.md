# passwordGenerator

Description: ///


generateBtn.addEventListener("click", writePassword);

var generateBtn = document.querySelector("#generate");

function writePassword() {
  var password = generatePassword();
  var passwordText = document.querySelector("#password");
  passwordText.value = password;
}
