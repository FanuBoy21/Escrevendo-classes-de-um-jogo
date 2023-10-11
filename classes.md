//Introduza o do usuário
const nome=''

//Introduza a idade
const idade=''

//O tipo de lutador [Guerreiro,Mago,Monge,Ninja]
let tipo='Monge'

//Se a escolha for mago
if(tipo==='Mago'){class heroi{
    constructor(Mago){
      this.Mago=Mago
    }
}

let ataque= new heroi('magia')
console.log(`O ${tipo} atacou com ${ataque.Mago}.`)    
}

//Se a escolha for Guerreiro
else if(tipo==='Guerreiro'){class heroi{
    constructor(Guerreiro){
      this.Guerreiro=Guerreiro
    }
}
let ataque= new heroi('espada')
console.log(`O ${tipo} atacou com ${ataque.Guerreiro}.`)    
}

//Se a escolha for Monge
else if(tipo==='Monge'){class heroi{
    constructor(Monge){
      this.Monge=Monge     
    }
}
let ataque= new heroi('artes marciais')
console.log(`O ${tipo} atacou usando ${ataque.Monge}.`)    
}

//Se a escolha for Ninja
else if(tipo==='Ninja'){class heroi{
    constructor(Ninja){
      this.Ninja=Ninja  
    }
}
let ataque= new heroi('Shuriken')
console.log(`O ${tipo} atacou com ${ataque.Ninja}.`)    
}
