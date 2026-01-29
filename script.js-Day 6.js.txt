let user = {
    fullname:"Manshi Chaudhari",
    address:{
        city:"Gurugram",
        state:"Haryana",
    },
    mobile:123456789,
    favcolor:["Black","white","blue"]
    demo:function (){
        return "demo function";
    }


}

console.log(user.fullname, user.moblieno, user.favcolor[i],
     user.address.city);

//return statement itself work as break statement
//object.key in form of arrays return case

console.log(object.entries)
//2-D arrays
[
    [key,value]
]   
//interview question
//[["x", "0", "x"]]  
  [["0","x", "0"]]
  [["0", "x", "x"]]














const car ={
    make: "Mahindra",
    mode: "Thar"

};
//we can't add a new key and valuw pair but we can change or update existing values
Object.seal(car);

//we can't add a new key and valuw pair but we can change or update existing values
Object.freeze(car);

car.model ="XUV700";
car.color = "Black";
console.log(car);
