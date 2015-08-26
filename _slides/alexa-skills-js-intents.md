---
order: 7
group: alexa-skill-js
group_order: 2
---

# Intent Handlers

The real meat of a Alexa Skill, you defined them in your Alexa interface setup. The AlexaSkillsKit figured out via voice which is being called, you provide the function to actually perform it:

```
myskill.prototype.intentHandlers = {
  IntentName: function(intent, session, response){
    // do your thing
    response.tell('hello world')
  },
  HelpIntent: function (intent, session, response) {
    response.ask('This is your help, now what?');
  }
};
```
