```
fun main(){
    var a = 0
    var x = 5
    if (x%2==0){
        a=1
    }
    else{
        a=2
    }
    print(a)
}
```

can also be written as:
```
fun main(){
    val x = 5
    val a = if(x%2==0) 1 else 2
    print(a)
}
```