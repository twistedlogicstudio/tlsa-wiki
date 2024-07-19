#TLSA #TLSALearn 
- - -
![[🚩 P.A.R.A/3. Resources/Assets • Media/TLSA Banner.png]]

# UVR (Ultimate Vocal Remover) Tutorial 

> [!note] 
> The UVR 5 [Official Website](https://ultimatevocalremover.com/)
> Download UVR from their [Github Page](https://github.com/Anjok07/ultimatevocalremovergui)  
> The latest release, as well as legacy versions are listed here [UVR GUI Releases](https://github.com/Anjok07/ultimatevocalremovergui/releases) 

# What's UVR?
UVR (Ultimate Vocal Remover) is a free tool utilising different AI models to separate vocals & instrumentals, as well as splitting tracks into stems. [^1]

# Settings & How To Use 

### UVR 5's Application Window
After installing, open up the application. The Window should appear like below. 

Once you know how to set it up & what each of the different settings do, try all of the different models out. Once you've tried them all, look at downloading extra models, you might just find something a little extra specific for your needs.

![[UVR 5 App.png]]
## Using the App

> [!note]
> ***TIP!***
> Hover over the title of each section to see the 'tooltips' or an Overview of the setting and what they do.

#### 1. Selecting Input & Output
- **INPUT:** This is to select the file / track / audio you want to process
- **OUTPUT:** This is to select the location for the files after processing

#### 2. Choosing the Process Method
This is to select the model used for processing the file / track / audio

- I'd almost always choose **Ensemble Mode** 
	- As you can choose multiple different models as well as more specific models *eg:*
		- VR Architecture - De Echo Agressive

#### 3. Choosing the Stem Pair
This setting is for choosing how you want UVR to split the file / track / audio. 
Depending on what you need, you can split just the Vocals & Instrumental, Drums / No Drums, Bass / No Bass, or a mixture of them 

- I'd pick **Multi-Stem Ensemble**
	- As this will split the audio ~ stacking multiple models, processing as per Model Chosen *eg:*
		- Vocal Remover model + Instrument Split Model + De-Noise Model:
			- 1x Vocal / 1x Instrumental
			- 1x Drums / 1x Bass / 1x Synths
			- 1x De-noise Vocal / 1x De-noise Instrumental

#### 4. File Type & Ensemble Algorithm
- **File Type:** This is for choosing the file type that UVR will export to
	- I'd pick **WAV** almost every time - as it's better quality than MP3, and more widely used compared to FLAC
	- If file size is a concern - use **MP3**

- **Ensemble Algorithm:** This is for choosing the quality of the Splits
	- Max Spec - the audio will be processed at the highest quality possible

#### 5. Ensemble Options
This is used for **Ensemble Mode:** 

- when using multiple models, you can save them here, to quickly run it again without having to configure all of the settings again

#### 6. Available Models
When using a multiple model mode, this is where you can select all of the models you want to use.

- Notable Models to use / try:
	- VR Arch: De-Echo
	- VR Arch: HP UVR
	- MDX-Net: Kim Vocal
	- MDX-Net: InstVoc HQ
	- Demucs: htdemucs

#### 7. Settings & Start Processing
The wrench icon is to open the settings tab & the 'Start Processing' button is to begin the audio split.

In the settings you can download extra models - extra models of note:
- Vocals
	- UVR-MDX-NET-Voc_FT
	- MDX32C (either 8K FFT, Full Band (v1) or 8K FFT, Full Band (v2))  
    optional: htdemucs_ft

- Instruments / Instrumentals
	- MDX32C
	- UVR-MDX-NET-Inst_HQ_4
	- Optional: You can add htdemucs_ft (for drums and bass) or htdemucs_6d (to separate piano and guitar as well)


- - -
# Resources
- [UVR 5 Clean Vox Extract - Github Discussion](https://github.com/Anjok07/ultimatevocalremovergui/discussions/689)
- [UVR 5 Tips 2024](https://multimedia.easeus.com/ai-article/how-to-use-ultimate-vocal-remover.html)
- [UVR 5 Guide - G-Doc](https://contacts.google.com/widget/hovercard/v/2?origin=https%3A%2F%2Fdocs.google.com&usegapi=1&jsh=m%3B%2F_%2Fscs%2Fabc-static%2F_%2Fjs%2Fk%3Dgapi.gapi.en.MGCxJbnW_Xw.O%2Fam%3DAAAg%2Fd%3D1%2Frs%3DAHpOoo9xa4htLEVH9xe6c4ToUehtTaLWvA%2Fm%3D__features__#id=I__HC_94253229&_gfid=I__HC_94253229&parent=https%3A%2F%2Fdocs.google.com&pfname=&rpctoken=11970416)
- [UVR 5 Best Settings - Reddit](https://www.reddit.com/r/audioengineering/comments/1bh84b5/ultimate_vocal_remover_5_best_settings_to_use/)
- [UVR 5 Best Settings - AudioSEX](https://audiosex.pro/threads/ultimate-vocal-remover-5-best-settings-for-best-results.71505/)
- [UVR 5 Medium Article](https://medium.com/@tanalpha-aditya/revolutionising-source-separation-ultimate-vocal-remover-app-emerges-victorious-bedba482791b)

- - -
# Footnotes

[^1]: Link to Glossary Page / Stems vs Multitracks Page