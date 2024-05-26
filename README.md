# SI_2024_lab2_215082
Elena Gjurevska 215082

2. ![Control Flow Graph](https://github.com/elenagjurevskaa/SI_2024_lab2_215082/assets/165379989/77b835c2-ac9d-4fc4-a7fb-b7000cfe02ac)
 
3. Цикломатската комплексност е 11, според бројот на региони во CFG на функцијата.
4. -[], 0
   
   -name=[],barcode=[],payment=0
   
   -name='apple',barcode='12347',discount='',payment='300',price='310'
   
   -name='apple',barcode='123a47',discount='',payment='300',price='300'
   
   -name='apple',barcode='012347',discount='5',payment='1000',price='600'

  5. Поради тоа што имаме еден услов со 3 подуслови со формулата 2^3=8 ни требаат 8 test cases
   
   if (item.getPrice() > 300 && item.getDiscount() > 0 && item.getBarcode().charAt(0)== '0')

  -price='600',discount='10',barcode='012347'
  
  -price='600',discount='10',barcode='12347'
  
  -price='600',discount='0',barcode='012347'
  
  -price='600',discount='0',barcode='12347'
  
  -price='200',discount='10',barcode='012347'
  
  -price='200',discount='10',barcode='12347'
  
Ние треба да имаме 8 теста но бидејки во if подусловите ни се поврзани со И според кое ако било кој од подусловите не е точен  тогаш  повлекува целот if да не биде извршен.

  
  

