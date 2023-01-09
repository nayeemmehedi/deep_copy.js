# deep_copy.js

const value ={
    name :{
        sub:"bangla"
    }
}

const nayeem ={...value}
const nayeemChange = JSON.parse(JSON.stringify(nayeem))

nayeemChange.name.sub= "english"

console.log(value)
