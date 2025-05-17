# Tide-of-Truth
Tide of Truth is an educational game developed for high school classroom
Game Design of “Tide of Truth”


AI Prompt
Create a game in twine following the design document for “Tide of Truth” by writing Twine Harlowe code for each scene and block. 

Variables:
Player Level: “Beginner”, “Assistant”, “Scientist”, and “Leading Scientist” with “Beginner” as initial value.
Credit: numeric value from 0 - 200. Initially 0. Add 50 when player pass job interview
A, B, C, D are the model coefficients in trigonometry formula f(x) = A sin (B(x+C))+D.
Player level and credit will be displayed in a title bar on top of each screen.
Random variable landfallTime is chosen from values of 0-9
Logical variable for the decisions to fortify the dam: isDamFortified: True / False
Countdown variable hourLeft will be set to 60 hours, count down will start when player is working in the lab on the new model.

Calculation specification will be given in the design document. Calculation code would be organized in blocks that’s not visible.

Narratives vivid and positive tone with sense of urgency according to the situation. Each screen should have no more than 3 lines of narrative except for the player choices.

Character:
The playable character is a young climate scientist, Jackie or whatever play chooses, hired by a coastal city council, eager to prove their math knowledge can be beneficial to society well beings.
NPC Jamie is a rookie journalist, eager to prove himself at the Stormhaven Sentinel the local paper that his investigation will communicate truth that a wide audience needs. As one option, he brought data he collected from lighthouse log, and fishermen.
NPC archive librarian who offered main character a old document with missing pages which have partial information of the old tide forecast model.

Back Story
In Tide of Truth, players take on the role of, a young scientist, in the coastal town of Stormhaven. Jackie, who passed interview and gets a assistant scientist job working in the city Hurricane Taskforce,  is examining the looming hurricane data, construct trigonometric functions to help the city council to make decisions to protect the communities.

Main Character’s Goals:
predicting tidal cycles to protect the shoreline community and marine life by investing in dam upgrades to fend off dangers from the tide in upcoming hurricanes.
Sub-goals include, first get the job by passing the interview, and second, as an assistant, successfully analyze the existing data by finding the correct parameters of the old forecasting model so to get promoted to scientist which need a minimum of 100 credit. And thirdly, create new model with reliable data, which can be used in forecasting tide level at the hurricane landfall time.

Obstacles:
1. Interview with several questions in order to get hired
2. As assistant, gain credit by researching the parameters of the old model, i.e. midline, amplitude, frequency etc.
3. Once promoted to the scientist, need to acquire and analyze data in order to create new model with correct coefficient of A, B, C, and D.

Game story structure
Tide of Truth is a choose your own adventure type of structure. The character will get data from interacting with NPCs, i.e. Jamie the journalist obtained from interviewing old lighthouse keeper, or the archived document with missing pages . If the main character becomes a scientist by successfully analyze and recover the parameters of old model, will be chartered to create a new model. If the correct model is not created in given time countdown, the level will get back to assistant. Either scientist with new model,  or main character at assistant level whether downgraded from scientist or never get promoted, will be able to use the correct model to forecast the tide level at give landfall time represented by a random x value. The final decision by the town council base on the model forecast is if the tide dam is fortified by higher walls. Character win when the water level (tide level plus wave of the landfall) is contained by the dam fortified or not. Player loose when community gets flooded. Player loose when water level is below the dam when fortification decision is made. Random variable of Landfall timing will be ranged so 80% chance of overflow of the dam if not enforce.

Game Scene

Section 0: introduction
Prompt player for preferred name, gave some description of the  main character as a hook, offer a choice to wait before getting started.

Section 1: 
When player choose to start the game, describe the back story.
Offer player to request for an interview. 
Player answers the following questions by free choice from the list

Question #1: A right triangle has legs 7 km & 24 km. How long is the hypotenuse?
Correct answer: 25KM, incorrect answers: 14KM, 17KM, 31KM

Question #2: in right triangle, $$sin\theta = 3/4$$. The Side opposite is 9 m. What is the hypotenuse?
Correct answer is 12m, incorrect answers are 7.5m, 6m, and 3m.

Question #3: if the hypotenuse is 5m and the opposite side is 4m, what is the sine of the angle.
Correct answer is 0.80, and the incorrect answers are 1.60, 1.25, and 3.00. 

Player can try as many time as they want. In case of mistakes, scaffolding URL provided for further study:  https://youtu.be/77XAdyWz5SM

When all correct answer selected, player’s level will be changed from beginner to Assistant and credit increase from 0 to 50. Screen will present the congratulations and welcome the player by printed chosen name, to join the team by participating a Tidal-Model Bootcamp.

Section 2: Tidal-model Bootcamp

Player is welcomed to the bootcamp. The city council official announce the purpose is the evaluate the existing model by digging any information from the archive. Recover it and evaluate it.

The player “you” are going to the archive. The Librarian found a partial document with only a page of a chart. On the chart, some data marked. All the other pages are damaged and the content is illegible.

You can choose to  study the parameters. If you get one parameter right, you gain 20 credit, if you get it wrong, you loose 5 credit. You can only gain 20 credit once. In case of mistake, URL will be provided for scaffolding study: https://voxeledphoton.itch.io/trigonometry and https://www.youtube.com/watch?v=Zpp0dlV3D0k

Parameter 1: Midline, correct answer is -8, incorrect answers are -18, 14, and 2. in case of mistake, provide the definition as a hint: In a sine function, the midline is the horizontal line that represents the average value of the function, halfway between its maximum and minimum points.

Parameter 2: Amplitude, correct answer is 10, incorrect answers are -8, 18, and 6. in case of mistake, provide the definition as a hint: The amplitude determines the maximum distance the function oscillates above or below its midline. It is represented by the absolute value of the coefficient 'A' in the general form y = A sin(Bx + C) + D.

Parameter 3: Period, correct answer is 16, incorrect answers are 2\pi, \pi/8, and 10. in case of mistake, provide the definition as a hint: the period refers to the horizontal distance it takes for one complete cycle of the sine wave to occur. For the standard sine function, y = sin(x), the period is 2π. 

If your credit is less than 100 after studied all parameters, you will be offered to join the war room to use a model that’s been worked out by other scientist, and make decision for dam fortification and get the end state.

If you credit is equal to or more than 100, your will be able to get promoted to scientist and enter the lab to create new model.

Section 3: lab
You will have to collect data for new model as a scientist. You can choose from meeting with Journalist Jamie who offer the old lighthouse log.
Or you can choose to retrieve data from the weather buoys.

Both ways can enable you to put up a chart. You can use the chart to figure out the parameters of the function f(x)=A sin (B(x+C))+D. The A, B, C, and D in the formula can be filled by a pull down selection list of options.

In the list for A, correct choices are: 5.0, 4.8 , Incorrect choices are: 1.0, 3.3, 12.4, 36\pi, 5\pi
In the list for B, correct choices are: 11/14, \pi/4,  Incorrect choices are  22/7, 1.57, 3.42, 2\pi, and 10.
In the list for C, correct choices are: 6.0, 5.8; Incorrect choices are 3\pi/2, 11/14, 22/7, 4.9, and 13.6. 
In the list for D, correct choices are: 10, 11, and 9;  Incorrect choices are 12, 15, 8, and 5.  

Remind player that Pi can be approximated as 22/7. A small inaccuracy can be accepted.

Because the hurricane Calypso is reported to be approaching Stormhaven very soon. The 60 hour countdown is started now. And the countdown hour will be shown on the title bar.

If time is up, you will be send back to the bootcamp, your credit reduced to 50, you level return to assistant. You can choose to go to the war room from there.
 
When all the parameters are selected, you can choose to feed in a super computer to verify. The result will cause change of credit.

If you get all correct, you will be able to claim to have the right model and enter the war room as scientist.
If you get  3 of the parameters correct, you will be encouraged to try again without credit change
If you get 2 correct, you will be encouraged to try again with 10 credit deducted each time.
If you get only one correct, you will be encouraged to try again with 20 credit  deducted.
If you get all wrong, you will be encouraged to try again with 50 credit deducted.
If your credit is less than 20, you will be sent back to bootcamp while your level returns to assistant.

In the screen offering retrying, also provide URL for scaffolding study: https://www.geogebra.org/m/cuCwguXP


Section 4 war room
The war room is where the officials and scientists assistant monitoring the hurricane Calypso, review the forecast, make recommendation and action.
By presenting the forecasting model in a chart developed by a scientist, you will recommend for the city to use emergency budget to fortify the dam to prevent flooding.
Or you can choose not to fortify the dam hoping it can contain the water level at the landfall of hurricane Calypso the huge wave of which will increase the water level by 3-7 meters.

End state:

“Community protected”, when isDamFortified is True and landfallTime is 1-8, or when isDamFortified is false and landfallTime is 9 or 0, because the fortified dam contained water level at which dam without fortification would not be able to or the water level is not reaching the original dam.
“Community over-protected”, when isDamFortified is True and landfallTime is 0, 9 because the fortification is no use when the water level is below the original dam.
“Damaged by flooding”, when isDamFortified is false and landfallTime is 1-8.

All the end states offer options to replay.







