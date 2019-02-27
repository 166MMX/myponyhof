---
title: my ponyhof
---

# my [ponyhof][wiktionary]
If life would be all like sunshine and rainbows

* [EFI][uefi] boot service driver implementation of [APFS][apfs] to be able to boot [macOS Mojave][mojave] with [VirtualBox][vbox], preferably written in [Rust][rust]
* [DAB+][dabp] stream recorder library with [ensemble][mux] listing support, supporting RTL2832U. Main goal is to have a highly energy efficent stream recorder that avoids to transcode the stream. The resulting binary should target hardware like a [Raspberry Pi][berrypie].
* [Roland MT-32][mt32] [daughterboard][daughterboard] having [opto-isolators][optoisolators] to directly connect to the 16bit [PCM][pcm] [parallel bus][parallelcom] on the mainboard of the MT-32. The daughterboard would only be a "passive" board in terms of logic that only provides connectivity to the PCM bus. It would be permanantly installedinto the MT-32. This provides the ability to directly capture the PCM audio stream bypassing the [DAC][dac] to [ADC][adc] in order to elliminate any possible [signal noise][signalnoise] picked up during analog transmission and possible [ground loop][groundloop]. It would then be possible to achive a noise free clean audio recording of [midi][midi] files composed for the MT-32. These could then be archived with a lossless encoded file.

[wiktionary]: //de.wiktionary.org/wiki/das_Leben_ist_kein_Ponyhof#%C3%9Cbersetzungen 
[rust]: //www.rust-lang.org/
[apfs]: //developer.apple.com/support/apple-file-system/Apple-File-System-Reference.pdf
[vbox]: //www.virtualbox.org/
[uefi]: //wiki.osdev.org/UEFI
[mojave]: //en.wikipedia.org/wiki/MacOS_Mojave
[dabp]: //en.wikipedia.org/wiki/Digital_audio_broadcasting#DAB+
[heaac]: //en.wikipedia.org/wiki/High-Efficiency_Advanced_Audio_Coding
[mux]: //en.wikipedia.org/wiki/Multiplexing#Digital_broadcasting
[berrypie]: //en.wikipedia.org/wiki/Raspberry_Pi
[pcm]: //en.wikipedia.org/wiki/Pulse-code_modulation
[daughterboard]: //en.wikipedia.org/wiki/Expansion_card#Daughterboard
[optoisolator]: //en.wikipedia.org/wiki/Opto-isolator
[mt32]: //en.wikipedia.org/wiki/Roland_MT-32
[dac]: //en.wikipedia.org/wiki/Digital-to-analog_converter
[adc]: //en.wikipedia.org/wiki/Analog-to-digital_converter
[groundloop]: //en.wikipedia.org/wiki/Ground_loop_(electricity)
[parallelcom]: //en.wikipedia.org/wiki/Parallel_communication
[signalnoise]: //en.wikipedia.org/wiki/Noise_(electronics)
[midi]: //en.wikipedia.org/wiki/MIDI
