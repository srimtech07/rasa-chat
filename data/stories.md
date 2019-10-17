## story_greet <!--- The name of the story. It is not mandatory, but useful for debugging. -->
* greet <!--- User input expressed as intent. In this case it represents users message 'Hello'. -->
 - utter_greet <!--- The response of the chatbot expressed as an action. In this case it represents chatbot's response 'Hello, how can I help?' -->

## story_goodbye
* goodbye
 - utter_goodbye

## story_thanks
* thanks
 - utter_thanks




## story_switch_01
* switch{"switchType":switchType}
  <!-- - utter_affirm_switch -->
  <!-- * affirm{"response":"yes"} -->
  <!-- - action_reset_slot -->
  - utter_switch


<!-- ## story_switch_01_1
* switch{"switchType":"Marketing Activities"}
  - utter_affirm_switch
  * denial{"response":"no"}
    - action_reset_slot
    - utter_cancel_switch -->

<!-- ## story_switch_02
* switch{"switchType":"Design Studio"}
  - utter_switch
  * affirm{"response":"yes"}
    - utter_switch
    - action_reset_slot

## story_switch_02_1
* switch{"switchType":"Design Studio"}
  - utter_switch
  * denial{"response":"no"}
    - utter_cancel_switch
    - action_reset_slot

## story_switch_03
* switch{"switchType":"My Marketo"}
  - utter_switch
  * affirm{"response":"yes"}
    - utter_switch
    - action_reset_slot

## story_switch_03_1
* switch{"switchType":"My Marketo"}
  - utter_switch
  * denial{"response":"no"}
    - utter_cancel_switch
    - action_reset_slot -->

## story_expiry_04
* expire{"duration":"week"}
  - utter_expire

## story_expiry_05
* expire{"duration":"day"}
  - utter_expire

## story_expiry_06
* expire{"duration":"hour"}
  - utter_expire
