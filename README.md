# postcards-from-my-jungle
## Strategies for training the model
For training the models, I tried to experiment with the different parameters available to me. I increased and decreased things like the number of epochs or the database size. For the prompts I tried to keep them varied by describing the same thing with differing language. 

## How I trained the model
Making the images was done with a database of sea lion images. I started generating with the default resolution of the boilerplate code. First I increased the epochs and noticed less messy images. Then I changed the resolution down and the images went from blue to yellow. I brought back up the resolution and lowered the database size. That changes the colors back to a more blue and purple. After that, I pushed to 100 epochs. The images turned out much cleaner but still pretty blurry. My last attempt had me half the epochs and increase the resolution. It created these odd green squares. 

To make the sounds I gave various prompts describing what I wanted.
“Jungle animal noises”
“Amazon rainforest sounds”
“Zoo animal sounds”
“Sea lion sounds”
The results were similar sounds of animals and what you would expect from the jungle. The only odd one is the AI definitely misinterpreted “Sea lion” as “Sea” sounds, given the audible seagull.

## Ideas for future improvements
Overall I think it could be vastly improved with several hundred more epochs, bigger images and more training data. It’s a bit of an obvious answer but with the results here, it’s very clear that’s what would improve it the most. I would also say that the biggest difference came from changing the resolution of the images. So perhaps that might be a priority for future iterations. For the sounds, it would just need more descriptive prompting. The language I think turned out alright. My biggest takeaway from this project is the scale of large language models is so much bigger than I can imagine to get the level of output we get today.
