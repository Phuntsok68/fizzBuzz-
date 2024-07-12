# fizzBuzz-

    function fizzBuzz(){
    for(let i=1;i<=100;i++){

     if(i%3===0 && i%5===0){
        console.log('fizzbuzz');
        continue;
     }

     else if(i%3===0){
        console.log('fizz')
        continue;
     }
     else if(i%5===0){
        console.log('buzz');
        continue;
     }
   
     console.log(i);

     }
     }

    fizzBuzz();

    ********************************

    var output=[];
    let i=1;
    function fizzBuzz(){

    if(i%3===0 && i%5===0){
        output.push('fizzbuzz');
        
    }
    else if(i%3===0){
        output.push('fizz');
    }
    else if(i%5===0){
        output.push('buzz');
    }
    else{
    output.push(i);
    }
    i+=1;
    console.log(output);
    
    }
    fizzBuzz();

    ********************************
    function fizzBuzz(){
    var output=[];
    for(let i=1;i<101;i++){
       
    
    if(i%3===0 && i%5===0){
        output.push('fizzbuzz');
        
    }
    else if(i%3===0){
        output.push('fizz');
    }
    else if(i%5===0){
        output.push('buzz');
    }
        else{
         output.push(i);
        }
    }
    return output;
    
    }
