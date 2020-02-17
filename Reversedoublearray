function balik2d (input){
var reverse1=[];
for (var i=input.length-1; i>=0;i--){
        reverse1.push(input[i]);
        
      }
      
      var awal = reverse1[0];
      var akhir=reverse1[reverse1.length-1];
      var balikAwal="";
      var balikAkhir="";
      
      for (var j=awal.length-1; j>=0;j--){
      balikAwal+=awal.charAt(j);
        
      }
      for (var k=akhir.length-1; k>=0;k--){
      balikAkhir+=akhir.charAt(k);
        
      }
 if (reverse1[0]===awal){
   reverse1[0]=balikAwal;
 }
 if(reverse1[reverse1.length-1]===akhir){
   reverse1[reverse1.length-1]=balikAkhir;
 }
      
console.log(reverse1); 
}
balik2d(['rabu', 'cinta', 'benci', 'masuk']);
