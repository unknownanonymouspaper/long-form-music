⚠️ *Warning: This website may not function properly on Safari. For the best experience, please use Google Chrome.*



## Long-form music generation: comparison with state-of-the-art with Song Describer Dataset prompts

**Prompt**: This song contains someone strumming a melody on a mandolin while more people are whistling along. Then a mandolin, an e-bass and an acoustic guitar are playing a short melody in a lower key before breaking into the next part along with flutes and percussions. This song may be played outside by musicians performing. 

| Our Model | MusicGen-large-stereo  | 
| *(stereo, 44.1kHz)* | *(stereo, 32kHz)* |
| ------ | -------------- | 
| <audio controls preload=False><source src="audio/1001_sa2.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/1001_musicgen.wav" type="audio/mpeg">Audio not supported by your browser.</audio> |

**Prompt**: This song contains someone strumming a melody on a mandolin while more people are whistling along. Then a mandolin, an e-bass and an acoustic guitar are playing a short melody in a lower key before breaking into the next part along with flutes and percussions. This song may be played outside by musicians performing. 

| Our Model | MusicGen-large-stereo  | 
| *(stereo, 44.1kHz)* | *(stereo, 32kHz)* |
| ------ | -------------- | 
| <audio controls preload=False><source src="audio/94_sa2.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/94_musicgen.wav" type="audio/mpeg">Audio not supported by your browser.</audio> |

**Prompt**: UNKNOWN SO FAR

| Our Model | MusicGen-large-stereo  | 
| *(stereo, 44.1kHz)* | *(stereo, 32kHz)* |
| ------ | -------------- | 
| <audio controls preload=False><source src="audio/906_sa2.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/906_musicgen.wav" type="audio/mpeg">Audio not supported by your browser.</audio> |


**Prompt**: The commercial music features a groovy piano melody played over snare rolls in the first half of the loop. Right after, there is a drop that consists of a punchy "4 on the floor" kick pattern, shimmering hi hats, claps, groovy piano and wide synth lead melody. It sounds happy, fun, euphoric and exciting.

| Our Model | MusicGen-large | Ground-truth | 
| *(stereo, 44.1kHz)* | *(mono, 32kHz)* | *(stereo, 44.1kHz)* |
| ------ | -------------- | --------------- | --------- |
| <audio controls preload=False><source src="audio/1069_sa2.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/1969_musicgen.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/1069.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> |

**Prompt**: The commercial music features a groovy piano melody played over snare rolls in the first half of the loop. Right after, there is a drop that consists of a punchy "4 on the floor" kick pattern, shimmering hi hats, claps, groovy piano and wide synth lead melody. It sounds happy, fun, euphoric and exciting.

| Our Model | MusicGen-large | Ground-truth | 
| *(stereo, 44.1kHz)* | *(mono, 32kHz)* | *(stereo, 44.1kHz)* |
| ------ | -------------- | --------------- | --------- |
| <audio controls preload=False><source src="audio/1091_sa2.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/1091_musicgen.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/1091.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> |

**Prompt**: UNKNOWN SO FAR

| Our Model | MusicGen-large | Ground-truth | 
| *(stereo, 44.1kHz)* | *(mono, 32kHz)* | *(stereo, 44.1kHz)* |
| ------ | -------------- | --------------- | --------- |
| <audio controls preload=False><source src="audio/3_sa2.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/3_musicgen.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/3.mp3" type="audio/mpeg">Audio not supported by your browser.</audio> |

These prompts/audios were used for the qualitative study we report in our paper.


## Memorization analysis

<audio controls preload=False><source src="94/original.flac" type="audio/mpeg">Your browser does not support the audio element.</audio>

<audio controls preload=False><source src="94/original.flac" type="audio/mpeg">Your browser does not support the audio element.</audio>

| Generation by our model | Closest #1 | Closest #2 | Closest #3 | Prompt |
| ----------------------- | ---------- | ---------- | ---------- | ------ |
| <audio controls preload=False><source src="audio/94/original.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.796563">796563</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.1083119">1083119</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.634461">634461</a>| "One cannot avoid moving the feet and neck listening to this fast and loopy brazilian tune". |
| <audio controls preload=False><source src="audio/1001/original.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.279428">279428</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.1082095">1082095</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.326758">326758</a>| "An uplifting jazz song that makes your head shake". |
| <audio controls preload=False><source src="audio/1091/original.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.1024058">1024058</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.1023046">1023046</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.788950">788950</a>| "Calming instrumental music primarily on piano can be used for relaxing". |
| <audio controls preload=False><source src="audio/1069/original.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.470048">470048</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.470047">470047</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.696082">696082</a>| "This song starts with a ukulele and builds up with percussion using claps and an acoustic guitar that plays the same rhythm as the ukulele with melody played on a xylophone and has a very upbeat feel to it". |
| <audio controls preload=False><source src="audio/427105/original.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.427160">427160</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.427105">427105</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.140843">140843</a>| "bird". |
| <audio controls preload=False><source src="audio/978535/original.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.978924">978924</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.979616">979616</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.978717">978717</a>| "chiptune". |
| <audio controls preload=False><source src="audio/972457/original.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.979544">979544</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.979695">979695</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.979670">979670</a>| "classical". |
| <audio controls preload=False><source src="audio/978661/original.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.972466">972466</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.972983">972983</a>| <a href="https://www.audiosparx.com/sa/summary/play.cfm/crumb.31/crumc.0/sound_iid.973055">973055</a>| "chiptune". |


## Additional creative capabilities

