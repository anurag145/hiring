
# Platform Frontend Intern Role

  

## Tooling

We at Vernacular.ai use various tools to support our CCA and ASR platform, some of which are interfaces that we have created for ourselves designed specifically for our use-case. Every interface tries to solve a fundamental problem.


### Problem Statement 1

Your task is to create an interface which does the following:

- Upload an Image to the interface which is of dimension 1024 x 1024.

- The image should be previewed. The user will now have two options which are:
	- Options one will take a user to a screen where the image is already cropped into 4 dimensions from the center of the image where they can select(choose) one of the 4 options. The dimensions are:
		- 800 x 600 
        - 400 x 450  
        - 365 x 212
        - 300 x 300
   - Options two will take a user to a screen where the user can manually crop the image, this will be considered the chosen image.
  
 - The image should be cropped and not stretched.
 
 - Any other dimension apart from 1024 x 1024 should be rejected.
 
 - After the final image has been chosen. The interface will upload this image to Imgur and display the image link generated by Imgur.
 
#### Bonus Point
- Styling. Using any CSS framework is highly discouraged.
- Hosting it on any service.

#### Reading Link(s)
- **[https://apidocs.imgur.com/?version=latest](https://apidocs.imgur.com/?version=latest)**


### Problem Statement 2
Your task is to create an interface which consists of the following:
 
-   A card that has two input boxes where a user can enter text.  
      
-   The user will then be able to record the statement he has given as inputs.  
      
-   The interface will provide the user with an option to listen to what they have recorded and re-record it.  
      
-   A card here can be viewed as a snippet of a conversation between two people.  
      
-   The interface will allow users to add multiple snippets by providing a button on the screen to add more snippets.  
      
-   The interface will also give an option to delete a snippet.  
      
-   Input box 1 and its recording will be considered to be the “BOT”, input box 2 and its recording will be considered to be a “Customer”.  
      
-   The interface now allows these audios recorded in the snippets to be stitched together so that it appears as if the Bot and the customer are speaking on a call.  
      
-   The interface will have an option to preview the audios stitched together without downloading the stitched audio file.  
      
-   The interface will allow the user to download the generated audio file, along with the transcription which is a JSON file, You can decide what all metadata you want to save in this file apart from the text.  
      
-   For the stitched audio the interface will add 1500ms of silence between the Customer and the Bot and will add 750ms between Bot and Customer.

#### Bonus Point
- Snippets can be swapped. 
- Styling. Using any CSS framework is highly discouraged.
- Hosting it on any service.

### Instruction for the Candidate
-  Please note we expect this challenges to be completed with either [ReactJS](https://reactjs.org/) or [Elm Lang](https://elm-lang.org/). Angular, Vue.js and Ember or even VanillaJs will not be entertained.

-  Please ensure your code is available on Github.  
      
-  You will be judged for your approach. We also recommend using a linter to maintain code hygiene.  

- Documentation explaining how to use the Interface.  
      
