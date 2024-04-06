<p>Bu repository belli bir amaç için gerekli olan kuşbakışı görselleri içeren Stanford verisetini amaca yönelik ayıklamak ve uygun veri dönüşümlerini sağlamak ile ilgileniyor.</p>
<p>-verisetlerini içeren video,merged,merged_squeezed,sub_ds klasörleri kasıtlı olarak eksiktir.</p>
<p>
  labels2loc-> stanford'un etiket yapısını koordinatlı biçime dönüştürür.(x1,y1,x2,y2)
</p>
<p>
  stanford_vid2im-> belli sayıda frameleri atlayarak videodaki frameleri resim olarak kaydeder.
</p>
<p>
  test_merged_ds ve test_tag_on_frame-> koordinatlı türdeki ve birleştirilmiş son haldeki verisetini görsel olarak gözden geçirmeye yarar.
</p>
<p>
  sub_ds dosyaları-> Verisetindeki otomatik etiketli verilerin bazıları yanlış etiketler içeriyor aslında olmayan 
  insanları etiketliyor. Bu nedenle az sayıda veriyi ayıklıyoruz ve etiketliyoruz ardından bu verilerle minik bir tf model eğitiyoruz. 
  Eğittiğimiz model ile verilerin tekrardan üzerinden geçerek insan içermeyenleri ayıklıyoruz. 
  
</p>
