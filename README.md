# ejemplo
First type of example

Interfaz -> conjunto de mensajes que tienen un objeto. Las interfaces son distintas si tienen nombre distinto
Los parámetros son objetos. Los objetos tienen identidad propia.
El * y + son mensajes 

object pepita{
       var energia = 100
       method comer(gramosAlpiste){
       energia = energia + 2 * gramosAlpiste}
       
       method volar(kms){
       energia = energia - kms/10}}
       
object pepo{
       var energia = 120
       method comer(gramosAlpiste){
       energia = energia + 10 * gramosAlpiste}}
       
object boing747{
       var nafta = 0
       method volar(kms){
       nafta = nafta - (kms / 1030)}
       
       method cargar(litros){
       nafta = nafta + litros}}
