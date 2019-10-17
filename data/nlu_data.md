<!--- Make sure to update this training data file with more training examples from https://forum.rasa.com/t/rasa-starter-pack/704 -->

## intent:goodbye <!--- The label of the intent -->
- Bye 			<!--- Training examples for intent 'bye'-->
- Goodbye
- See you later
- Bye bot
- Goodbye friend
- bye
- bye for now
- catch you later
- gotta go
- See you
- goodnight
- have a nice day
- i'm off
- see you later alligator
- we'll speak soon

## intent:greet
- Hi
- Hey
- Hi bot
- Hey bot
- Hello
- Good morning
- hi again
- hi folks
- hi Mister
- hi pal!
- hi there
- greetings
- hello everybody
- hello is anybody there
- hello robot

## intent:thanks
- Thanks
- Thank you
- Thank you so much
- Thanks bot
- Thanks for that
- cheers
- cheers bro
- ok thanks!
- perfect thank you
- thanks a bunch for everything
- thanks for the help
- thanks a lot
- amazing, thanks
- cool, thanks
- cool thank you

## intent:affirm
- yes [yes](response)
- yes sure [yes](response)
- absolutely [yes](response)
- for sure [yes](response)
- yes yes yes [yes](response)
- definitely [yes](response)
- yup [yes](response)
- yo [yes](response)
- yeah [yes](response)
- fine [yes](response)

## intent:denial
- no [no](response)
- nope [no](response)
- n [no](response)
- na [no](response)

## intent:switch
- Switch to [Marketing Activities | Design Studio | My Marketo | GlobalLogic](switchType)
<!-- - Switch please to [Marketing Activities](switchType)
- Switch [Marketing Activities](switchType)
- [Marketing Activities](switchType) switch please
- Switch to [Marketing Activities](switchType) please
- I want to switch to [Marketing Activities](switchType)
- Can you switch to [Marketing Activities](switchType)
- Please switch to [Marketing Activities](switchType)
- [Marketing Activities](switchType) switch
- Do switch to [Marketing Activities](switchType)
- Make switch to [Marketing Activities](switchType) -->
<!-- - Switch to [Design Studio](switchType)
- Switch please to [Design Studio](switchType)
- Switch [Design Studio](switchType)
- [Design Studio](switchType) switch please
- Switch to [Design Studio](switchType) please
- I want to switch to [Design Studio](switchType)
- Can you switch to [Design Studio](switchType)
- Please switch to [Design Studio](switchType)
- [Design Studio](switchType) switch
- Do switch to [Design Studio](switchType)
- Make switch to [Design Studio](switchType)
- Switch to [My Marketo](switchType)
- Switch please to [My Marketo](switchType)
- Switch [My Marketo](switchType)
- [My Marketo](switchType) switch please
- Switch to [My Marketo](switchType) please
- I want to switch to [My Marketo](switchType)
- Can you switch to [My Marketo](switchType)
- Please switch to [My Marketo](switchType)
- [My Marketo](switchType) switch
- Do switch to [My Marketo](switchType)
- Make switch to [My Marketo](switchType) -->

##intent:expire
- Give me [assets|smartcampaign|landing pages](assetsType) expiring in [1](number) [Week|Hour|Day](duration)
- Do give me assets expiring in [2](number) [Week](duration)
- Please give me assets expiring in [5](number) [Week](duration)
- I want assets expiring in [8](number) [Week](duration)
- I want to get assets expiring in [16](number) [Week](duration)
- Can I get assets expiring in [24](number) [Week](duration)
- Can you help me to get assets expiring in [30](number) [Week](duration)
<!-- - Give me assets expiring in [1](number) [Day](duration)
- Do give me assets expiring in [2](number) [Day](duration)
- Please give me assets expiring in [5](number) [Day](duration)
- I want assets expiring in [8](number) [Day](duration)
- I want to get assets expiring in [16](number) [Day](duration)
- Can I get assets expiring in [24](number) [Day](duration)
- Can you help me to get assets expiring in [30](number) [Day](duration)
- Give me assets expiring in [1](number) [Hour](duration)
- Do give me assets expiring in [2](number) [Hour](duration)
- Please give me assets expiring in [5](number) [Hour](duration)
- I want assets expiring in [8](number) [Hour](duration)
- I want to get assets expiring in [16](number) [Hour](duration)
- Can I get assets expiring in [24](number) [Hour](duration)
- Can you help me to get assets expiring in [30](number) [Hour](duration) -->

##intent:regex_number
- [0-9]{2}
