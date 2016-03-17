# helloWorld
my first repository


#Javascript
var hello = 'hello World@c1hyt0k@gmail.com';
var pattern =/^\w+\s\w+@[a-zA-Z0-9]+@\w+(\.\w+)+$/;
document.getElementsByName('username_email').onblur = function (){
    alert(pattern.test(hello));
}
