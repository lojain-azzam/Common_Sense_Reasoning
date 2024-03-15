# Common_Sense_Reasoning
To build a system that can outperform a baseline model with an accuracy of 0.2 using fastText, word2vec, and GloVe word embeddings. Additionally, compare the performance of these pretrained embedding models in terms of accuracy.

* Task Description: * 
You are provided with a file containing a number of multiple-choice questions (MCQs), where each question has the correct answer. The questions are related to common sense reasoning.

Data Format:
Each question in the file is represented as a JSON object with the following format:
{
  "answerKey": "A",
  "id": "075e483d21c29a511267ef62bedc0461",
  "question": {
    "question_concept": "punishing",
    "choices": [
      {
        "label": "A",
        "text": "ignore"
      },
      {
        "label": "B",
        "text": "enforce"
      },
      {
        "label": "C",
        "text": "authoritarian"
      },
      {
        "label": "D",
        "text": "yell at"
      },
      {
        "label": "E",
        "text": "avoid"
      }
    ],
    "stem": "The sanctions against the school were a punishing blow, and they seemed to what the efforts the school had made to change?"
  }
}


 }
