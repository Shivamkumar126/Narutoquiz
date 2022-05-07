function play(question, answer){
    var score =0;
    var readLineSync=require("readLine-sync");
    var userAnswer = readLineSync.question(question);
    if(userAnswer===answer){
      console.log("right");
      score++
    }
    else{
      console.log("wrong");
    }
    
    console.log(score);                                    
  }
 
  var questions= [
    {
      question: "who was the father of Naruto?    ",
      answer: "Minato",
    },
    {
      question: "Who was the ghost of the uchiha clan ?  ",
      answer: "Madara uchiha",
    },
    {
     question:"Who was the real brother of sasuke uchiha?    "  ,
     answer: "Itachi uchiha",
    },
    {
      question:"Real name of the nine tailed beast?  ",
      answer: "Kurama",
    },
    {
      question:"Gara belongs to which village ?   ",
      answer: "Hidden sand",
    }, 
  ];
  for(var i=0; i<questions.length;i++){
    currentQuestion=questions[i];
    play(currentQuestion.question,currentQuestion.answer);
  }