//ATIVIDADE 1


import 'dart:math';

void main() {
  List<int>randomList=List.generate(50,(_)=>Random().nextInt(100)+0);
  var list = [];
  
var numeros = <int>[-1,-2,-15,-67,-25,-30,-74,-80,-99,-55];
print(numeros);

randomList.sort((y,x)=> x.compareTo(y));
print(randomList);

final reverseOrder = randomList;
print(reverseOrder.toList());
bool x = false;
 for (var i in randomList){
  if (i >= 10){
    list.add(i);
  }
  if (i == 77){
    x = true;
  }
 }

 print(list);
 if (x){
  print("77");
 }else {
  print("Não tem 77");
 }
 
 
}
