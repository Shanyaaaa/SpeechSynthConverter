import gtts
import playsound
print("hi! This is robo speaker")

text = input("enter what you want to speak:")
sound = gtts.gTTS(text, lang="en")
sound.save("welcome.mp3")
playsound.playsound("welcome.mp3")
