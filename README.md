# halloween_prank
It is time to scare you friends on halloween this 15 lines of python can scare you an your friends a lot!!
I have done it by using Pycharm which is an python code editor.
For the code I have used a pip (python installation package) which is **pip install pygame**
I have installed the package in the terminal.
Now in the first I have imported pygame.
Then I have written from time import sleep.
Then we have written pygame.init()
After that I have created a variable called window and have entered the value as pygame.display.set_mode((0, 0), pygame.FULSCREEN) so this code wil make the pygame default Fullscreen
.
Then for both the sounds I have written pygame.mixer.init().
Then for the first sound I have written pygame.mixer.music.load('ratsasan.mp3')
And to play the first sound I have written pygame.mixer.music.play()
Then the first ound should run for 5 seconds so I have written sleep(5).
Then to make the image and the second sound mix I have written pygame.mixer.music.load('scary.mp3')
pygame.mixer.music.play()
sleep(1)
image = pygame.image.load('scr.jpg')
window.blit(image, (0,0))
pygame.display.update()
sleep(3)
Now your prank is ready!! It is time to prank your friends on Halloween!!
