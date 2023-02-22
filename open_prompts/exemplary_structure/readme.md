## Exemplary Structure
### Categories
`Structure`
### Description
We have a letter from Tarzan from the jungle to Jane. We want to process this letter and put the relevant information in the JSON. Below you can see the full prompt where we first have that letter, then the processing instructions, and an example JSON structure.
### Examples

#### Example1
Prompt
```
Consider the following message:
```

Response
```
{
  "sender": "Tarzan",
  "message": "Dear Jane, I am thinking about you when I am swinging through the jungle. Greetings, Tarzan",
  "list_of_words": [
    "Dear",
    "Jane",
    "I",
    "am",
    "thinking",
    "about",
    "you",
    "when",
    "I",
    "am",
    "swinging",
    "through",
    "the",
    "jungle",
    "Greetings",
    "Tarzan",
  ],
  "addressed": "Jane",
  "amount_of_words": 16
}
```

### Source
<https://blog.devgenius.io/how-to-get-gpt3-to-output-in-json-4e14c46aa5b6>
