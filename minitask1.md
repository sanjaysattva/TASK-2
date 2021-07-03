# EC07 Smart Spectacles for Auditorily impaired

**Problem statement**

Inorder to  grab the attention of deaf people immediately , we have to inevitably get in their field of view or touch them . Such is the daily scenario in the life of a deaf person, who is
unfortunately constrained only to procure critical data from their immediate field of view.

We propose to improve the situational awareness of auditorily impaired people by notifying the direction of the sound source in their environment. We propose to 
create a smart spectacles for the auditorily impaired , which signals the direction of sounds in their vicinity by signalling 
with LED lights on the spectacles .


**Pipeline**

The one-line of this project is to receive sounds from the surroundings , process the direction of sound and signal using LEDs on the spectacles . 

We need microphones to input sounds from the surrounding , microcontroller to process the input to give output , and LEDS to signal the direction of sound .

We use an array of microphones to detect the sounds from the surroundings , however the spectacles cant support too many microphones . Thus we 
use MEMS microphones , which are very small and multiple numbers of them can be employed. Also . MEMS microphones can be directly connected with 
microcontrollers.MEMS technology is advantageous and convenient compared to Electret Condenser Microphone

We can use low power consuming microcontrollers like Arduino or  ESP32 microcontroller.

 ESP32 microcontroller has bluetooth and wi-fi which arduino lacks , thus it is preferrable . Additionally , its cheaper . We can also use the custom dev board of the electronics club 
 which is  developed around the ESP32 WROOM SoC and comes with WiFi and Bluetooth functionalitie.
 
 LEDs are used without a question. We employ multiple colours for different scenarios , for say , red for immediate sounds at vicinity like automobile horns.
 
 If we detect the direction of sounds by comparing the intensity of the sound from different sides, we can eploy omnidirectional mics. If we use only frequency modulation , 
 we may employ directional mics itself . 
 
 This project will require expertise in fourier transforms and programming , also different sound processing algorithms.
