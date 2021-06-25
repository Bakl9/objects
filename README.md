# objects

            const summer = Object.assign ({
                tume: "12-mp",
                goold: 'time',
                name: 'Miky'
            }).   

            const Newsummer = Object.assign ({}, summer,{
                email:'commencal@mail.ru'
            })

            console.log(Newsummer)
 const newspapaer = Object.assign ({
                time: '12-mp',  
                auto: 'bmw',
                name: 'ilysha',
            })

            const newee = Object.assign  ({}, newspapaer ,{
                emeil: "@mail.ru"
            })
            
            
                console.log(newee)
// let user = {
            //     name: 'John',
            //     age: 30
            // };

            // let key = prompt ('Что вы хотите узнать о пользователе?' , 'name');

            // alert( user [key] );


            // let fruit = prompt('Какой фрукт купить?', 'Apple');

            // let bag = {
            //     [fruit]: 5,
            // };

            // alert( bag.apple);


// let obj = {
//     test: undefined 
// };

// alert( obj.test );
// alert( 'test' in obj );



// let user = {
//     name: 'John',
//     age: 30,
//     isAdmin: true
// };

// for (let key in user){
//     alert( key );

//     alert( user[key] );
// }


// let codes = {
//     '49': 'Германия',
//     "41": "Швейцария",
//     "44": "Великобритания",
//     "1": "США"
// };

// for (let code in codes) {
//     alert(code);
// }


let codes = {
    "+49": "Германия",
    "+41": "Швейцария",
    "+44": "Великобритания",

    "+1": "США"
};

for (let code in codes) {
    alert( +code );
}

 const user = Object.assign ({
                age: 30,
                name: 'Ilysha',
            })

            const newUser = Object.assign ({}, user ,{
                email: 'commencal@mail.ru'
            })

            console.log(newUser)


const person = Object.assign({
    name: 'Ilsha',
    age: 25,
    id: 'owerTools',
});

const NewPerson = Object.assign({}, person, {
    mail: "@mail.ru",
});

console.log(person);
console.log(NewPerson);

console.log(Object.keys(person)) // метод для проверки индекса в обьекте
console.log(Object.values(person)) // метод для проверки 
console.log(Object.entries(person)) // получает сразу развернутый массив
Object.freeze(person)
person.name = 'Ivan' /// мотод замораживает обьект и делает его не изменным
Object.freeze(person) // изменяет обьект, нужно будет затестить как он работает))
person.name = 'Ivan'

const isPerson = Object.is(person, newPerson); // is метод стравнивает


