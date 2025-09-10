# Next-Gen Education: Integrating LLM and Reinforcement Learning in Teaching and Learning
An APP to generate puzzle using LLM

Please follow the steps provided below to execute the project :

1. Download the trained LLM model from the provided link and place it in the project directory :  
https://huggingface.co/Nandini82/Llama-2-7b-chat-finetune-qa-meta-GGUF/tree/main
2. Open the project in VS Code.
3. Start the backend by running the following command in the terminal : flask run
4. Once the backend starts, click on the "Open Live Server" option at the right bottom of the window. This will redirect you to a webpage.
5. On puzzle webpage, paste any text content from which the puzzle should be generated. Then, select the number of words to generate and click on Submit.
6. You will be redirected to the puzzle page. (Note : There might be a delay since the model might require some time for processing. For faster response, try using the content on which the model was trained. An example of the trained content is provided below.)
7. Click the Start button to begin solving the crossword. The agent will guide you step by step as you solve, helping you complete the puzzle.
8. Enjoy solving the puzzle !

Here's an example of the trained content :

"Blood is a vital fluid in our bodies, composed mainly of plasma and various types of cells. Plasma, the liquid part, carries nutrients and waste. Red blood cells transport oxygen, powered by the pigment hemoglobin, giving blood its red color. White blood cells are immune system defenders, combating infections. Platelets aid in clotting, preventing excessive bleeding. Blood vessels, including arteries, veins, and capillaries, distribute blood throughout the body. The heart pumps blood through these vessels, ensuring oxygenation and waste removal. Valves maintain one-way blood flow, generating the heartbeat's characteristic sound. The pulmonary circuit connects the heart and lungs for oxygenation. Pulse, felt in arteries, reflects heartbeats per minute. In the excretory system, waste removal occurs via kidneys, which filter blood, producing urine. Ureters transport urine to the bladder, where it's stored and expelled through the urethra. Dialysis substitutes kidney function when necessary. In pl ants, transportation happens through osmosis, root hairs increasing surface area for water absorption, and vascular tissues (phloem and xylem) distributing nutrients and water. Transpiration, loss of water vapor through leaves, aids in water absorption and distribution."
