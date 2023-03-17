# day3task

//for the given Json iterate over all for loops
let marks=
{
    tamil:84,
    english:88,
    maths:94,
    science:89,
    social:95,
    total:450
};
//for in loop
for (let key in marks )
{
    console.log(key, ':', marks[key]);
}
//for of loop
for( let key of Object.keys(marks))
{
    console.log(marks[key])
} 
let num=[10,20,30,40,50];
//for loop
for(let i=0;i<num.length;i++)
{
    console.log(num[i])
}
//foreach loop
let names = ['anitha','swetha','kavitha'];

names.forEach((number, index, names) => {
   console.log(number, index, names[index]); 
});

//create your own data in JSON format
let myresume=
{
    name: 'K.bhavani Lakshmi',
    email: 'bhavanilakshmi533@gmail.com',
    phoneno:6374358835,
    skills:
    {
        1:"front end development",
        2:"web designing"
    },
    strength:
    {
        1:"Fast learner",
        2:"time management"
    },
    langugae:
    {
        1:"tamil",
        2:"english"
    },
    
};
for (let key in myresume )
{
    console.log(key, ':', myresume[key]);
}
