# CV - Gatsev Igor
__Contacts:__ 
1. Mail: _wise61mouse@mail.ru;_
1. Skype: _TitusMan16;_ 
1. _+996 555 775377;_

## About me

I am 35 years old, currently I am an Android developer. On the course I want to improve my knowledge of Web development


## My skills: 
* Basic JS, HTML5, CSS3;
* Sass;
* Git; 
* C# ;
* Java;
* Android Develop

## Code Example
```html
    btnAdd.addEventListener('click', function(){
    var val = valueValidate.value;
     if(val != ""){
        if(hidFieldsList.value.includes(val))
        {
         alert("Введеное значение уже есть в списке валидации.");
        }  else {
         hidFieldsList.value += val + '"';
         fieldsValidate.innerHTML+= '<button id=' + valueValidate.value + ' class="addedValue"  type="button" onClick="deleteClick(this); storeValue()">' + valueValidate.value.trim() + '</button>';
        }
     } else {
       alert("Пустое значение");
     }
    });

    function deleteClick (e){
        var btn = document.getElementById(e.id);
        btn.remove();
    }

    function storeValue() {
            var src = document.getElementsByClassName('addedValue');
            var selected = document.getElementById('hidFieldsList');

            selected.value = "";

            for (i = 0; i < src.length ; i++) {
                selected.value += src[i].innerText.trim() + "@@";
            }
    	}
```

## English Level
My english level A2.
