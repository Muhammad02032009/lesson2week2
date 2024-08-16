# Lecture 4
$$ About-->Recursion
$$

  __What is recursion in  JS ?__

*   Recurse in funksiyae meboshad ki dar holati ba kor daromadan khudro boz faryod mekunad.
*   rcurs hatman yagon shartro qabul mekunad
  ```javascript
 function num(str)
 {
     if (str==0)
         {return 1}
         return str*num(str-1)
     }
     console.log(num(5));
```
____
$$ About-->Closur 
$$
  __What is closure in  JS ?__

* in funcsiyae meboshad ki dar daruni khud yakchand funcsiyaro qabul mekunad 
* infarmatsiyahoi funksiyai berunaro fuuncsiyai daruna girifta metavonad ammo darunaro  beruna nametavonad.
```javascript
function f1()
{
     let cnt=0
    return f2=()=>{
        return cnt+=1
    }
}
let d=f1()
console.log(d());
```