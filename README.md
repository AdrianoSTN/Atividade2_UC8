# Atividade2_UC8
//Sistema de Eventos


let nomeEvento  = " evento de teste  " ;
let dataEvento  = new Date( " 2022-02-24 " );
let hoje        = new Date();
let palestrante = " Fulano de Tal " ;

// Validar data do evento
   if (dataEvento < hoje){
     console.log( " Data Invalida " );
     }else{
     console.log( " Registra evento na base de dados " );
     }

// Cadastrar Participantes
let nomePart    = " participante " ;
let idadePart   = 14;

//Validar idade do participante
    if (idadePart < 18){
        console.log( " participante precisa ser maior de idade! " );
     }else{
        console.log( " Registrar partiipante na base de dados " );        
    } 

//Realizar inscrição
let qtdInscritos = 99;
    if (qtdInscritos >= 100) {
        console.log( " Não há mais vagas nesse evento! " );          
     }else{
        console.log( " Realizar inscrição no evento. " );
    }

//Listagem
let inscricoes = [{ evento: " evento1 " , palestrante: " Pedro " , participante: " Ruan " } , {evento: " aba de evento " , palestrante: " Rodrigo " , participante: " Jorge" }];
     for(i = 0; i < inscricoes.length; i++){
         console.log( inscricoes[i].evento + " - " + inscricoes[i].palestrante + " - " + inscricoes[i].participante);
     }
