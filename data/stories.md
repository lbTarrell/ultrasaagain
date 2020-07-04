## disappointment_path
* disappointment
 - action_storepreviousintent
 - utter_console_disappointment

## fear_path
* fear
 - action_storepreviousintent
 - utter_console_fear

## disapproval_path
* disapproval
 - action_storepreviousintent
 - utter_console_disapproval

## sadness_path
* sadness
 - action_storepreviousintent
 - utter_console_sadness

## grief_path
* grief
 - action_storepreviousintent
 - utter_console_grief

## admiration path
* admiration
 - action_storepreviousintent
 - utter_admiration

## amusement path
* amusement
 - action_storepreviousintent
 - utter_amusement

## anger path
* anger
 - action_storepreviousintent
 - utter_anger

## annoyance path
* annoyance
 - action_storepreviousintent
 - utter_annoyance

## approval path
* approval
 - action_storepreviousintent
 - utter_approval

## caring path
* caring
 - action_storepreviousintent
 - utter_caring

## confusion path
* confusion
 - action_storepreviousintent
 - utter_confusion

## curiosity path
* curiosity
 - action_storepreviousintent
 - utter_curiosity

## desire path
* desire
  - action_storepreviousintent
  - utter_desire

## disgust path
* disgust
  - action_storepreviousintent
  - utter_disgust

## embarrassment path
* embarrassment
  - action_storepreviousintent
  - utter_embarrassment
  - action_searchjoke
  - action_telljoke

## excitement path
* excitement
  - action_storepreviousintent
  - utter_excitement

## gratitude path
* gratitude
  - action_storepreviousintent
  - utter_gratitude

## joy path
* joy
  - action_storepreviousintent
  - utter_joy

## love path
* love
  - action_storepreviousintent
  - utter_love

## nervousness path
* nervousness
  - action_storepreviousintent
  - utter_nervousness
  - utter_comfort

## optimism path
* optimism
  - action_storepreviousintent
  - utter_optimism

## pride path
* pride
  - action_storepreviousintent
  - utter_pride

## realization path
* realization
  - action_storepreviousintent
  - utter_realization

## relief path
* relief
 - action_storepreviousintent
 - utter_relief

## remorse path
* remorse
  - action_storepreviousintent
  - utter_remorse

## surprise path
* surprise
  - action_storepreviousintent
  - utter_surprise

## greet path
* greet
 - action_storepreviousintent
 - utter_greet

## hot song path
* introduce_Song
 - action_searchsong
 - action_suggestsong

## playlist path
* music_playlist
 - action_suggestplaylist

## happy path
* inform
 - action_search_recipe
 - action_suggestion

## imlotatesting
* lotatest
 - utter_lottatesting

## New Story

* surprise
    - utter_lottatesting

## New Story

* greet
    - action_storepreviousintent
    - slot{"intent_name":"greet"}
    - utter_greet
* inform
    - utter_ask_target_calories
* inform{"targetcalories":"10000"}
    - slot{"targetcalories":"10000"}
    - slot{"targetcalories":"10000"}
    - action_search_recipe
    - slot{"title":"30 Minute Chorizo & Arugula Breakfast Hash with Lime Greek Yogurt Crema"}
    - slot{"readyInMinutes":25}
    - slot{"recipeID":625910}
    - slot{"sourceUrl":"http://www.lifeasastrawberry.com/chorizo-breakfast-hash/"}
    - slot{"instructions":"Cut the florets off the stems and and then chop them into tiny florets. You can also chop up the stems into tiny pieces if you want. You should have about 6 cups of chopped cauliflower. In a large skillet heat 2 tablespoons of olive oil over medium-high heat. Add the cauliflower, 1 teaspoon of salt, rosemary, and sumac. Sauté until cauliflower is tender and starts to brown a bit, stirring as necessary, about 15 minutes. You can also add a bit of olive oil if the pan starts to get too dry or the cauliflower is starting to stick. Meanwhile, in a small skillet, toast the pinenuts over medium heat until golden brown. Set aside. Heat the remaining 2 tablespoons of olive oil in the same pan. Once oil is shimmering, toss in the breadcrumbs and stir, toasting the breadcrumbs. Season with a pinch of kosher salt and a few turns of freshly ground black pepper. Remove from the heat and toss in half of the chopped parsley. When cauliflower is done, remove from the heat and season to taste with freshly ground black pepper and a pinch or so of salt if necessary. Toss in the toasted pine nuts, the chopped raisins, and the remaining parsley. When ready to serve, sprinkle the top with the toasted breadcrumbs and some pecorino."}
    - action_suggestion
    - slot{"targetcalories":"10000"}
* introduce_Song
    - slot{"targetcalories":"10000"}
    - action_searchsong
    - slot{"song":"Does To Me"}
    - slot{"singer":"Luke Combs Featuring Eric Church"}
    - action_suggestsong
    - slot{"targetcalories":"10000"}
* embarrassment
    - action_storepreviousintent
    - slot{"intent_name":"embarrassment"}
    - utter_embarrassment
    - action_searchjoke
    - slot{"joke":"“The digital camera is a great invention because it allows us to reminisce. Instantly.” – Demetri Martin"}
    - slot{"targetcalories":"10000"}
* joy
    - action_storepreviousintent
    - slot{"intent_name":"joy"}
    - utter_joy
    - slot{"targetcalories":"10000"}
* music_playlist
    - action_suggestplaylist
* admiration
    - action_storepreviousintent
    - slot{"intent_name":"admiration"}
    - utter_admiration
    - slot{"targetcalories":"10000"}
* bye
    - utter_bye

## New Story

* greet
    - utter_greet
* optimism
    - action_storepreviousintent
    - slot{"intent_name":"optimism"}
    - utter_optimism
* introduce_Song
    - action_searchsong
    - slot{"song":"The Box"}
    - slot{"singer":"Roddy Ricch"}
    - action_suggestsong
* admiration
    - action_storepreviousintent
    - slot{"intent_name":"admiration"}
    - utter_admiration
* inform
    - utter_ask_target_calories
* inform{"targetcalories":"10000000"}
    - slot{"targetcalories":"10000000"}
    - action_search_recipe
    - slot{"title":"Persimmons Pumpkin Orange Smoothie With Chia Seeds"}
    - slot{"readyInMinutes":45}
    - slot{"recipeID":655786}
    - slot{"sourceUrl":"https://spoonacular.com/persimmons-pumpkin-orange-smoothie-with-chia-seeds-655786"}
    - slot{"instructions":"Cut the florets off the stems and and then chop them into tiny florets. You can also chop up the stems into tiny pieces if you want. You should have about 6 cups of chopped cauliflower. In a large skillet heat 2 tablespoons of olive oil over medium-high heat. Add the cauliflower, 1 teaspoon of salt, rosemary, and sumac. Sauté until cauliflower is tender and starts to brown a bit, stirring as necessary, about 15 minutes. You can also add a bit of olive oil if the pan starts to get too dry or the cauliflower is starting to stick. Meanwhile, in a small skillet, toast the pinenuts over medium heat until golden brown. Set aside. Heat the remaining 2 tablespoons of olive oil in the same pan. Once oil is shimmering, toss in the breadcrumbs and stir, toasting the breadcrumbs. Season with a pinch of kosher salt and a few turns of freshly ground black pepper. Remove from the heat and toss in half of the chopped parsley. When cauliflower is done, remove from the heat and season to taste with freshly ground black pepper and a pinch or so of salt if necessary. Toss in the toasted pine nuts, the chopped raisins, and the remaining parsley. When ready to serve, sprinkle the top with the toasted breadcrumbs and some pecorino."}
    - action_suggestion
* admiration
    - action_storepreviousintent
    - slot{"intent_name":"admiration"}
    - utter_admiration
