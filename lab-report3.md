# Lab Report 3

## grep -c
    $ grep -c "you" written_2/non-fiction/OUP/Abernathy/*.txt
    written_2/non-fiction/OUP/Abernathy/ch1.txt:0
    written_2/non-fiction/OUP/Abernathy/ch14.txt:1
    written_2/non-fiction/OUP/Abernathy/ch15.txt:0
    written_2/non-fiction/OUP/Abernathy/ch2.txt:1
    written_2/non-fiction/OUP/Abernathy/ch3.txt:1
    written_2/non-fiction/OUP/Abernathy/ch6.txt:1
    written_2/non-fiction/OUP/Abernathy/ch7.txt:0
    written_2/non-fiction/OUP/Abernathy/ch8.txt:10
    written_2/non-fiction/OUP/Abernathy/ch9.txt:0
    
The `grep -c` command gives an output of the number of lines that the text file contains the word inputted. This could be useful when someone is trying to find how many occurences of a particular word is found within each file.

    $ grep -c "the" written_2/non-fiction/OUP/Berk/*.txt
    written_2/non-fiction/OUP/Berk/ch1.txt:153
    written_2/non-fiction/OUP/Berk/ch2.txt:183
    written_2/non-fiction/OUP/Berk/CH4.txt:189
    written_2/non-fiction/OUP/Berk/ch7.txt:125
    
This command finds the number of times `the` is contained within each file in the specific directory. The ouptut gives the file name and the number of lines that contains the word.

---

## grep -v
    $ grep -v "the" written_2/travel_guides/berlitz1/HandRHongKong.txt

            Recommended Hotels
            Hotels listed below have full air-conditioning, offer 24-hour or
            limited room service, and a wide range of facilities. Hong Kong hotels
            have excellent business services and conference facilities; many have
            shopping malls.
            Reservations are strongly recommended, particularly in
            summer and at Christmas. If you do arrive without making advance
            International Airport will be happy to arrange accommodations for you
            on your arrival.
            indicate high-season rates in Hong Kong dollars, based on double
            major credit cards. A 10% service charge and 5% government tax will be
            $$$$above HK$2,500
            $$$HK$l,600 to HK$2,500
            $$HK$950 to HK$1,600
            $below HK$950
            
The `grep -v` command removes all occurrences of the given input in this case `the` and prints out the file without the word in it. This is useful when trying to remove a specific word from the whole file.

    $ grep -v "Los Angeles" written_2/non-fiction/OUP/Castro/chV.txt 
    
    Vaqueros (Cowboys)
    The vaquero was the early Hispano cowboy and the antecedent of the Hollywood cowboy. Horses and cattle were brought to New Spain by the Spaniards. When Hernán Cortés landed on the eastern shore of Mexico, he had with him sixteen horses and at least three breeds of cattle. Cattle breeding was a tradition hundreds of years old in Spain, and Cortés brought this tradition to Mexico and eventually to the Southwest. The Spaniards introduced the system of el rancho, with vaqueros being the workers who herded the cattle and conducting cattle drives. Vaca means “cow” and a vaquero is “one who works with cows.” The Spanish mission padres recognized this labor and conscripted mestizos (mixed-race people), Indians, and Mexicans to take care of the cattle. It was these individuals who developed the system, equipment, practices, and traditions that have lasted these past few hundred years. The Anglo cowboy learned everything about cattle from the vaquero.
    The Mexican vaquero was a laborer, a peon who was used by the missionaries to ride the horses and take care of the cattle. So it was the culture of the vaquero that became the basis for the romantic cowboy of Hollywood. The ensemble, equipment, and clothing of the vaquero evolved through the years as a combination of Spanish leather and regional indigenous fabrics. He always wore a sombrero with a wide brim, a leather chaqueta (jacket), tight-fitting knee-length sotas (breeches), and botas (leather leggings) for protection. The vaquero also wore iron spurs, like those worn by the Conquistadores, which are still worn to this day. The various styles of saddles, from the Moorish to the Spanish war saddle, eventually changed when the vaqueros began making their own saddles, more suitable for riding hard and for quick mounting and dismounting.
    The early vaqueros, those of the sixteenth and seventeenth centuries, were mestizos, Indians, Negroes, and mulattos. When Anglo Americans moved into Texas and bought enormous tracts of land, they established huge ranches and hired Mexican vaqueros to work them. They recruited and moved whole families from Mexico to work and live on their ranches. The King and Kennedy ranches of east Texas are contemporary examples of this tradition and have many generations of Mexican vaqueros still living on their ranches. A social historical study of the vaquero life on the King and Kennedy ranches, from the early nineteenth century to the present, has been written by Monday and Colley.
    The vaquero from California also worked on very large ranches, such as the Tejon ranch in the lower San Joaquin Valley. This way of life has been memorialized in the work of Arnold Rojas, who was a vaquero and has written about his life in California in the twentieth century. Rojas makes a distinction between the cowboy, the vaquero, and the buckaroo. The vaquero was originally Hispanic or Mexican, or Indian, and herded cattle in the Far West in the states of California, Nevada, Oregon, Arizona, Utah, and Washington, whereas the cowboys who herded cattle in the southern states were usually Negro or Anglo. The vaquero or buckaroo is a westerner and the cowboy is a southerner. The definition is a territorial one, with the cowboy working east of the Rockies and the vaquero west of the Rockies. It is this difference that Rojas writes about in his three-volume memoir of the California vaquero. Anglos coined the word buckaroo, meaning vaquero, because they disliked the word cowboy and did not want to call themselves by that name. Somehow when they pronounced vaquero, it came out of their mouths as “buckaroo.” The California Indians were trained by the Spanish missionaries to herd cattle, and they were the primary vaqueros until the mid-1800s. Mexicans from Sonora took over as vaqueros when they started migrating into California in the nineteenth century. The style of horse riding instituted by the Spaniards was called la jinete, a term that relates to the equipment used in riding. It not only includes the bits, spurs, and the saddles, but also the length of the stirrups, how the reins are held, and the amount of pressure of the knees on the horse. Rojas was born in California, as was his mother, who as a child had a pleasant encounter with the bandit Tiburcio Vásquez. He spent his whole life working as a vaquero and he states, “I speak as a vaquero—and I know whereof I speak” (Rojas, 1979, 119).
    References Graham 1990, 1991, 1993; Mather 1992; Monday and Colley 1997; Rojas 1958, 1979; Verti 1990
    Vásquez, Tiburcio (1835–1875)
    A legendary Chicano folk hero who roamed through California’s San Joaquin Valley during the late nineteenth century. He came from an old Californio family who owned extensive property and a large ranch. But he also lived during a time when Anglo Americans were becoming dominant in the state, when overt discrimination against Mexicans who were considered foreigners was on the rise, and he fell into a life of crime. Compared heroically to Joaquín Murrieta, Tiburcio Vásquez is regarded as a proud man who resisted social domination and fought to maintain and preserve his culture. He actually lived fairly long but was eventually captured, tried, and hanged at the age of forty.

This command removes the word `Los Angeles` from the whole text file. This might be useful when trying to censor or remove a location such as `Los Angeles` from a specifc text like this.

---

## grep -l

    $ grep -l "Japan" written_2/travel_guides/berlitz1/*.txt
    written_2/travel_guides/berlitz1/HandRJamaica.txt
    written_2/travel_guides/berlitz1/HistoryHawaii.txt
    written_2/travel_guides/berlitz1/HistoryHongKong.txt
    written_2/travel_guides/berlitz1/HistoryIndia.txt
    written_2/travel_guides/berlitz1/HistoryJapan.txt
    written_2/travel_guides/berlitz1/HistoryMalaysia.txt
    written_2/travel_guides/berlitz1/IntroIndia.txt
    written_2/travel_guides/berlitz1/IntroJapan.txt
    written_2/travel_guides/berlitz1/IntroLosAngeles.txt
    written_2/travel_guides/berlitz1/WhatToEgypt.txt
    written_2/travel_guides/berlitz1/WhatToFWI.txt
    written_2/travel_guides/berlitz1/WhatToHongKong.txt
    written_2/travel_guides/berlitz1/WhatToJapan.txt
    written_2/travel_guides/berlitz1/WhatToLosAngeles.txt
    written_2/travel_guides/berlitz1/WhereToDublin.txt
    written_2/travel_guides/berlitz1/WhereToFrance.txt
    written_2/travel_guides/berlitz1/WhereToHongKong.txt
    written_2/travel_guides/berlitz1/WhereToIndia.txt
    written_2/travel_guides/berlitz1/WhereToJapan.txt
    written_2/travel_guides/berlitz1/WhereToLosAngeles.txt
    written_2/travel_guides/berlitz1/WhereToMadrid.txt
    written_2/travel_guides/berlitz1/WhereToMalaysia.txt
    
The command `grep -l` takes the input and outputs only the file names with the word within the file. For this example, the files outputted were the only files within the directory that had Japan somewhere within the text.

    $ grep -l "unimaginative" written_2/travel_guides/berlitz1/*.txt
    written_2/travel_guides/berlitz1/IntroHongKong.txt
    written_2/travel_guides/berlitz1/WhatToJamaica.txt
    
This command causes only two files to show because these were the only files to contains the word. This could be useful to see if a certain word is obscure or not common within the directory.

---

## grep -i

    $ grep -i "finding" written_2/travel_guides/berlitz1/*.txt
    written_2/travel_guides/berlitz1/HandRIstanbul.txt:        Finding accommodation in Istanbul is rarely a problem, as
    written_2/travel_guides/berlitz1/HistoryEdinburgh.txt:        Finding his forces outnumbered and overextended here, the
    written_2/travel_guides/berlitz1/HistoryHawaii.txt:        Hawaiians were finding themselves overwhelmed and outnumbered. Disease
    written_2/travel_guides/berlitz1/HistoryIndia.txt:        tigers in the jungle were finding temples and palaces many Indians no
    written_2/travel_guides/berlitz1/HistoryItaly.txt:        a spiritual renewal, finding the perfect ally in Francis of Assisi
    written_2/travel_guides/berlitz1/IntroLosAngeles.txt:        Finding your way from one place to another is a major part
    written_2/travel_guides/berlitz1/WhatToEdinburgh.txt:        Finding one that suits you is all part of the fun. Most will serve
    written_2/travel_guides/berlitz1/WhatToEdinburgh.txt:        to find the tartan for you; otherwise, it is a matter of finding a
    written_2/travel_guides/berlitz1/WhatToFWI.txt:        have little difficulty in finding a boat to take you out. Such
    written_2/travel_guides/berlitz1/WhatToIsrael.txt:        Finding out what’s on: A children’s section appears in the
    written_2/travel_guides/berlitz1/WhereToEgypt.txt:        resulted in the finding of Tutankhamun’s treasure-filled tomb.
    written_2/travel_guides/berlitz1/WhereToGreek.txt:        Finding the most suitable Greek island for your style of
    written_2/travel_guides/berlitz1/WhereToIndia.txt:        Recent archaeological findings suggest that a site on the
    written_2/travel_guides/berlitz1/WhereToJerusalem.txt:        the minaret of a small mosque is the best landmark for finding the
    written_2/travel_guides/berlitz1/WhereToMalaysia.txt:        enjoy the rural and forested Malaysia. But finding your way around the
    written_2/travel_guides/berlitz1/WhereToMalaysia.txt:        surveyor, who in 1885 reported the finding of the “fine plateau. ” His
    written_2/travel_guides/berlitz1/WhereToMallorca.txt:        no trouble finding it. Steps lead down the hill through sprawling
    
The command `grep -i` is used to find specific words within files no matter the case the letters are. For this example, the output gives lines that included both `finding` and `Finding` because it ignores the case.

    $ grep -i "breakfast" written_2/travel_guides/berlitz1/*.txt
    written_2/travel_guides/berlitz1/HandRHawaii.txt:        free breakfast is a delight. 44 rooms.
    written_2/travel_guides/berlitz1/HandRHawaii.txt:        of bed & breakfast accommodations in the Volcano area. They have
    written_2/travel_guides/berlitz1/HandRHawaii.txt:        gourmet breakfasts and afternoon teas. 6 rooms.
    written_2/travel_guides/berlitz1/HandRHawaii.txt:        Breakfast included. 11 rooms.
    written_2/travel_guides/berlitz1/HandRIsrael.txt:        Gazit Menachem (Bed-and-Breakfast) ❁ Eilat Town; Tel. (07)
    written_2/travel_guides/berlitz1/HandRIsrael.txt:        breakfast, lunch, and dinner. Open-air bar, poolside restaurant, dining
    written_2/travel_guides/berlitz1/HandRIsrael.txt:        basic but clean. Breakfast included in the price of a room. 32
    written_2/travel_guides/berlitz1/HandRIsrael.txt:        featured in public areas and bedrooms. Room price includes breakfast.
    written_2/travel_guides/berlitz1/HandRIsrael.txt:        Price includes breakfast. 56 rooms.
    written_2/travel_guides/berlitz1/HandRIsrael.txt:        comfortable facilities for relaxation or BBQ. Breakfast served in
    written_2/travel_guides/berlitz1/HandRIstanbul.txt:        prices for a double room with bath, including breakfast:
    written_2/travel_guides/berlitz1/HandRJerusalem.txt:        substantial “Israeli” breakfast; in East Jerusalem, the price usually

    
This command finds every occurence of the word `breakfast` no matter the case of the letters. This could be useful when trying to find a word even when it starts with a captial letter.
