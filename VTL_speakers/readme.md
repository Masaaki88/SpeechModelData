#Speaker Group "srangefm" (speaker-group-female,male)
by Philip Zurbuchen

A range of speakers (male and female) between 0 years and 20.

In "srangefm_speakers/FileAge.txt" the speakerfiles are given their corresponding age in yrs and months. Format: "File" "Yrs" "Months" "Sex" \n
Sex: 0 = male, 1 = female

(So, the line "4 4 0 1" means that file '4.speaker' is of the age 4 yrs and 0 months and is female.)

Steps were 2 years. So two files (male and female) for 0 years, 2 files for 2 years (0, 1, 2, 3,) etc

- 	Gestures were created for each speaker with a specific pitch (fo frequency to age plotted in diagram). This was done using online data and interpolating for our speaker ages using a spine-fit.
	Online-'data' (just a figure): http://www.ncvs.org/ncvs/tutorials/voiceprod/tutorial/changes.html
	
-	chink length, chord rest length and chord rest thickness were linearly interpolated between infant an adult stage and changed in the .speaker files.

