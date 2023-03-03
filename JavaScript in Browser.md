# Brauzerdə JavaScript

İndi biz ilk JavaScript kodumuzu yazmağa hazırıq. JavaScript kodunu buraya yazmaq üçün bizə script elementi lazımdır. `Script` elementi əlavə edə biləcəyimiz iki yer var. 

-Biz `script` elementini  `head` bölməsinə və ya body bölməsinə əlavə edə bilərik.

-Ən yaxşısı `script` elementini bütün mövcud elementlərdən sonra əsas bölmənin sonuna qoymaqdır. Burada h1-dən sonra `script` elementini əlavə edək. Bu bizim `script` elementimizdir. İndi isə  niyə yaxşı olarki `script` elementini bura yerləşdiririk onun izahını verim? Bunun iki səbəbi var. 
  1. Səbəblərdən biri brauzerin bu faylı yuxarıdan aşağıya təhlil etməsidir .Belə ki , `script` elementini burada head bölməsinə yerləşdirsəniz . orada çoxlu JavaScript kodunuz ola bilər , ona görə də brauzeriniz həmin JavaScript kodunu təhlil etmək və icra etməklə məşğul olacaq. Beləliklə bu, saytınızın istifadəçiləri üçün pis təcrübə olacaq. Brauzeriniz JavaScript kodunuzu təhlil etmək və icra etməklə məşğul olarkən istifadəçiniz veb səhifənizə baxacaq, html və css kodlarının işləməsi gecikdiyindən müəyyən müddətlik o ağ və ya boş səhifə ilə qarşılaşacaq. 

2. İkinci səbəb, demək olar ki, həmişə `script` elementləri arasında olan kodun bu veb səhifədəki elementlərlə əlaqədə olması başqa cür desək danışması lazımdır. 

Məsələn Biz HTML elementlərinə JavaScript vasitəsilə təsir göstəririk. Bəzi elementləri göstərmək və ya gizlətmək istəyə bilərik. Ola bilərki stilində dəyişiklik edirik. Beləliklə, kodu buraya, `body` bölməsinin sonunda əlavə etməklə, bütün bu elementlərin brauzer tərəfindən göstərildiyinə əmin olacağıq. 
Bəzən istisnalar ola bilər beləki bəzən başlıq bölməsinə yerləşdirilməli olan üçüncü hissə kodundan buna third party code deyilir istifadə edə bilərsiniz. Ancaq bunlar istisnalardır, təcrübədə ən yaxşısı sizə dediyim kimi, JavaScript kodunuzu əsas bölmənin sonuna əlavə etməkdir. 
İndi burada, əvvəl browserdə yazmış olduğumuz, 
```javascript
 console.log("Hello World");
```

kodunu yazacayıq. Ancaq bu barədə bir az daha ətraflı danışacağıq, bu statement adlanır . Statement yəni bir ifadə yerinə yetirilməli olan hərəkəti ifadə edən kod parçasıdır. Bəzi ingilis dilində terminlər və ya proqramlaşdırmaya aid sözlər işlədəcəm amma hərfi tərcüməsini verməyəcm. Çünki bunlar hər zaman işə qəbul müsahibələrində belə ingilis dilində soruşulacaq. Bir növ buna hazirliq kimi düşünə bilərsiniz. Digər tərəfdən bəzən sözlərin tərcüməsi istifadə olunduğu sahəyə uyğun gəlmir. 
Davam edək bu halda, biz konsolda bir mesaj daxil etmək istəyirik. JavaScript-dəki bütün ifadələr nöqtəli vergüllə sonlandırılır. Burada tək dırnaqlar arasında olan şeyə `string`-sətir deyilir. `String` simvollar ardıcıllığıdır. indi JavaScript-də biz qeydlərimizi kod haqqında vacib şərhləri bildirmək üçün belə edirik iki tire yazırıq. və bu şərhi təmsil edir . Beləliklə, kodumuza bəzi şərhlər və ya qeydlər əlavə edə bilərik və bu şərh JavaScript mühərriki tərəfindən nəzərə alınmır, kod olaraq yerinə yetirilmir.
Ola bilərki siz komanda şəklində işləyirsiniz və yazdığınız kodu digər programçılara izah etmək üçün bu üsuldan istifadə edə bilərsiniz. Və ya bir proyekt işləyirsiniz üzərindən uzun zaman keçdikdən sonra xatırlamayacağsınız və ya xatırlamaq çox uzun vaxtınızı alacaq o zaman şərhlər sizə kömək ola bilər. 
Bu demo olduğu üçün mən sadəcə sadə bir şərh əlavə edəcəyəm, 

```javascript
 // Bu mənim ilk JavaScript kodumdur

```

 İndi dəyişiklikləri yadda saxlayaq , geri browser-ə qayıdaq , biz console-u geri gətirməliyik, ona görə də haradasa mouse-un sağ düyməsini klikləyin və inspectə daxil. Buradan console-u seçirik və `"Hello World"` mesajını görürük.
