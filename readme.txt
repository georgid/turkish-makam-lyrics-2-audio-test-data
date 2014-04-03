
This is readme about the test dataset for lyrics-to-audio alignment
This is a corpus of the classical turkish vocal form sarki.

NOTE: .txt files are in ISO-8859-9 encoding
To convert run: iconv -f ISO-8859-9 -t UTF-8 inputFile > outputFile
--------------------------
files contained: 
.txt - symbtr version 1.0 Format

author = {Karaosmano{\u{g}}lu, M Kemal},
  title = {A Turkish makam music symbolic database for music information retrieval:
	Symbtr},
  journal = {Proc. Int. Society for Music Information Retrieval (ISMIR)},
  year = {2012}


.pdf - full Score
.txtTur - Copy of lyrics (in original turkish script) from .pdf

to do evaluation of performance, Phrase-level annotation is : 
.TextGrid : tier phrases


.tsv - section annotations by note numbers in the score
.sectionAnno -  section annotations by timestamps in particular recording
.sectionLinks - discovered sections by timestamps in particular recording. Automatic section discovery algorithm: 

	author = {Sertan {\c S}ent{\"u}rk and Andr{\'e} Holzapfel and Serra, Xavier},
  title = {Linking Scores and Audio Recordings in Makam Music of Turkey},
  journal = {Journal of New Music Research},
  year = {In Press},


--------------------------

NOTEs on the nature of the songs: 

+++++++++++++
ussak--sarki--duyek--aksam_oldu_huzunlendim--semahat_ozdenses/01_Aksam_Oldu_Huzunlendim_Ben_Yine	quiet_accompaniment
ussak--sarki--duyek--aksam_oldu_huzunlendim--semahat_ozdenses/06_Semahat_Ozdenses_-_Aksam_Oldu_Huzunlendim	double_voice
muhayyerkurdi--sarki--duyek--ruzgar_soyluyor--sekip_ayhan_ozisik/1-05_Ruzgar_Soyluyor_Simdi_O_Yerlerde	
quiet_accompaniment

file://huzzam--sarki--curcuna--kusade_taliim--sevki_bey/06_Kusade_Talihim/06_Kusade_Talihim.mp3
quiet accompaniment

nihavent--sarki--aksak--bakmiyor_cesm-i--haci_arif_bey/04_Hamiyet_Yuceses_-_Bakmiyor_Cesm-i_Siyah_Feryade
nice voice, bad quality, with gazel. gazel used for adaptation 

nihavent--sarki--aksak--gel_guzelim--faiz_kapanci/18_Munir_Nurettin_Selcuk_-_Gel_Guzelim_Camlica'ya
nice voice, bad quality, with gazel. gazel part used for training 



---------------------------

acemkurdi--sarki--agiraksak--sevdi_gonlum--nikogos_aga/Hafiz_Kemal_Bey--Vasfini_Bu_Resme_Tertip_Ettiler
rec quality is so bad, that lyrics in some parts of vocal are unintelligible

hicaz--sarki--aksak--gulsen-i_husnune--rifat_bey/05_Aziz_Turk_Sanat_Muzigi_Grubu_-_Gulseni_Husnune_Kimler_Variyor
female choir all the time,  two vocals: one with echo of the second: check channels.
  but quiet accomapniment 

huseyni--sarki--turkaksagi--hicran_oku--sevki_bey/01_Koro_-_Hicran_Okur_Sinem_Deler
male and female voice in octave in whole song

huseyni--sarki--musemmen--hem_cemalin--zeki_duygulu/Koro--Canli_Fasil_8-Huseyni--Hem_Cemalin
female voice and choir behind in whole song, but female is predominant
a lot of vibrato


nihavent--sarki--aksak--bakmiyor_cesm-i--haci_arif_bey/15_Koro_-_Bakmiyor_Cesm-i_Siyah_Feryade
choir all the time, hard one


-----------
Scores are in symbTr format. 
A composition is matched to a musicBrainz id with the script: 
<musicBrainzProject>/sertanScores
Recordings are the recordings corresponding to a given composition matched from the music-brainz 

CRITERIA for selecting recordings in corpus: 

They have vocal (some performances of sarkis have a soloing instrument on the vocal )
They have one vocalist (some have two or more vocals)  




Georgi Dzhambazov
March 2014

