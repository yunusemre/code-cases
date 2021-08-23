````
for(let i = 0; i++; i<1000){
  setTimeout(() => console.log(i), 1000);
}

for (var i=0; i < 10; i++){
    setTimeout(() => console.log(i), 1000);
}
````

```
function kullaniciOlustur() {
  return {
    isim: "İhsan",
    ref: this
  };
};

let kullanici = kullaniciOlustur();

alert( kullanici.ref.isim );
````
