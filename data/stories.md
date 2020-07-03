## happy path
* greet
  - utter_greet
* affirm
  - utter_ask_target_calories
* inform{'targetcalories':2000}
  - action_search_recipe
  - action_suggestion
* goodbye
  - utter_goodbye

## sad path 
* greet
  - utter_greet
* deny
  - utter_next_time
  - utter_goodbye



