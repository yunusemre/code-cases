```|
function kullaniciOlustur() {
  return {
    isim: "İhsan",
    ref: this
  };
};

let kullanici = kullaniciOlustur();

alert( kullanici.ref.isim );
````
