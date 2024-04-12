⚠️ *Warning: This website may not function properly on Safari. For the best experience, please use Google Chrome.*



## Long-form music generation: comparison with state-of-the-art with Song Describer Dataset prompts

**Prompt**: An uplifting jazz song that makes your head shake. 

| Our Model | MusicGen-large-stereo  | 
| *(stereo, 44.1kHz)* | *(stereo, 32kHz)* |
| --------- | ---------------------- | 
| <audio controls preload=False><source src="audio/1001_sa2.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/1001_musicgen.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> |

**Prompt**: One cannot avoid moving the feet and neck listening to this fast and loopy brazilian tune.

| Our Model | MusicGen-large-stereo  | 
| *(stereo, 44.1kHz)* | *(stereo, 32kHz)* |
| --------- | ---------------------- | 
| <audio controls preload=False><source src="audio/94_sa2.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/94_musicgen.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> |

**Prompt**: Ambiental song that evokes calm with a progression of stereo electronic elements.

| Our Model | MusicGen-large-stereo  | 
| *(stereo, 44.1kHz)* | *(stereo, 32kHz)* |
| --------- | ---------------------- | 
| <audio controls preload=False><source src="audio/906_sa2.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/906_musicgen.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> |

**Prompt**: This song starts with a ukulele and builds up with percussion using claps and an acoustic guitar that plays the same rhythm as the ukulele with melody played on a xylophone and has a very upbeat feel to it.

| Our Model | MusicGen-large | Ground-truth | 
| *(stereo, 44.1kHz)* | *(mono, 32kHz)* | *(stereo, 44.1kHz)* |
| --------- | -------------- | --------------- | 
| <audio controls preload=False><source src="audio/1069_sa2.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/1969_musicgen.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/1069.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> |

**Prompt**: Calming instrumental music primarily on piano can be used for relaxing.

| Our Model | MusicGen-large | Ground-truth | 
| *(stereo, 44.1kHz)* | *(mono, 32kHz)* | *(stereo, 44.1kHz)* |
| --------- | -------------- | --------------- | 
| <audio controls preload=False><source src="audio/1091_sa2.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/1091_musicgen.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/1091.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> |

**Prompt**: A dance music club banger, with a heavy kick, subtle supporting percussion like tabla and bongos, prominent pop synth lines, and a repetitive hook.

| Our Model | MusicGen-large | Ground-truth | 
| *(stereo, 44.1kHz)* | *(mono, 32kHz)* | *(stereo, 44.1kHz)* |
| --------- | -------------- | --------------- | 
| <audio controls preload=False><source src="audio/3_sa2.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/3_musicgen.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/3.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> |

These prompts/audios were used for the qualitative study we report in our paper.


## Memorization analysis

<audio controls preload=False><source src="94/original.flac" type="audio/mpeg">Your browser does not support the audio element.</audio>

<audio controls preload=False><source src="94/original.flac" type="audio/mpeg">Your browser does not support the audio element.</audio>

| Generation by our model | Closest #1 | Closest #2 | Closest #3 | Prompt |
| ----------------------- | ---------- | ---------- | ---------- | ------ |
| <audio controls preload=False><source src="audio/427105.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.427160">427160</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.427105">427105</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.140843">140843</a>| Birds chirping, forest birds, tropical, africa wild life, singing birds, sound effects. |
| <audio controls preload=False><source src="audio/978535.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.978924">978924</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.979616">979616</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.978717">978717</a>| Full Mix. Totally rad 8-bit melodies and intense arps create that fearless throwback vibe. |
| <audio controls preload=False><source src="audio/972457.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.979544">979544</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.979695">979695</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.979670">979670</a>| No Melody. Pleasant strings create desire in this adamant scoring cue. |
| <audio controls preload=False><source src="audio/978661.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.972466">972466</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.972983">972983</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.973055">973055</a>| No Drums. Totally rad 8-bit melodies and intense arps create that strong-willed throwback vibe. |
| <audio controls preload=False><source src="audio/94_original.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.796563">796563</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.1083119">1083119</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.634461">634461</a>| One cannot avoid moving the feet and neck listening to this fast and loopy brazilian tune. |
| <audio controls preload=False><source src="audio/1001_original.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.279428">279428</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.1082095">1082095</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.326758">326758</a>| An uplifting jazz song that makes your head shake. |
| <audio controls preload=False><source src="audio/1091_original.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.1024058">1024058</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.1023046">1023046</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.788950">788950</a>| Calming instrumental music primarily on piano can be used for relaxing. |
| <audio controls preload=False><source src="audio/1069_original.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.470048">470048</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.470047">470047</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.696082">696082</a>| This song starts with a ukulele and builds up with percussion using claps and an acoustic guitar that plays the same rhythm as the ukulele with melody played on a xylophone and has a very upbeat feel to it. |


## Additional creative capabilities

**Audio-to-audio**
 With diffusion models is possible to perform some degree of style-transfer by initializing the noise with audio during sampling. This capability can be used to modify the aesthetics of an existing recording based on a given text prompt, whilst maintaining the reference audio's structure (e.g., a beatbox recording could be style-transfered to produce realistic-sounding drums). As a result, our model can be influenced by not only text prompts but also audio inputs, enhancing its controllability and expressiveness. We noted that when initialized with voice recordings (such as beatbox or onomatopoeias), there is a sensation of control akin to an instrument. 


**Vocal music**
The training dataset contains a subset of music with vocals. Our focus is on the generation of instrumental music, so we do not provide any conditioning based on lyrics. As a result, when the model is prompted for vocals, the model's generations contains vocal-like melodies without intelligible words. Whilst not a substitute for intelligible vocals, these sounds have an artistic and textural value of their own.

<audio controls preload=False><source src="audio/vocals1.mp3" type="audio/mpeg">Audio not supported by your browser.</audio>
<audio controls preload=False><source src="audio/vocals2.mp3" type="audio/mpeg">Audio not supported by your browser.</audio>
<audio controls preload=False><source src="audio/vocals3.mp3" type="audio/mpeg">Audio not supported by your browser.</audio>
<audio controls preload=False><source src="audio/vocals4.mp3" type="audio/mpeg">Audio not supported by your browser.</audio>
<audio controls preload=False><source src="audio/vocals5.mp3" type="audio/mpeg">Audio not supported by your browser.</audio>

**Short-form audio generation**
The training set does not exclusively contain long-form music. It also contains shorter sounds like sound effects or instrument samples. As a consequence, our model is also capable of producing such sounds when prompted appropriately. Examples of short-form audio generations are also on our demo page.


