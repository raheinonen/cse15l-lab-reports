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
    He was born in Monterey County in 1835 or 1837, where he was raised and attended school, becoming fluent in both English and Spanish. His career of flight and lawlessness started in 1851 when, with several other men at a fandango, he witnessed or was involved in the death of a constable named Hardimount. Not expecting to be treated justly, he fled to the hills, and from then on, Vásquez led a life of horse stealing, robbery, and hiding out in the foothills of California. The legend states that he shared his stolen goods with the poor Mexicans of the Salinas Valley. He was well liked and depended on the local people to hide him from the posses that were continually after him. He was captured several times and actually spent almost nine years in San Quentin prison, on two different occasions, first in 1857, then again in 1867. After being released in January of 1870, Vásquez spent the next four years in a life of banditry but also one of romance. Women were attracted to him and he frequently fell in love, and he had a special weakness for married women. He claimed to have never killed a single person, and when he robbed people in stores and stagecoaches, he’d tie them up and lay them face up on the ground, a tactic he used often during this period. One source refers to his “hog-tied” captives. He was shot and survived several times but was finally caught in May of 1874. While awaiting trial in the San Jose jail, Vásquez appealed for funds for his defense. Thousands of people came to visit him in jail, bringing flowers, food, and other gifts. With the funds raised he was able to hire two well-qualified lawyers. Even so, he was found guilty by a jury and sentenced to death. He was publicly hanged on March 19, 1875, in San Jose, California.
    There are many stories recounting the legendary exploits of Vásquez, especially those dealing with his romantic life, as he was considered a true Don Juan. On several occasions it was a lady that saved him from the legal authorities by helping to hide him. Once, at a party or fandango, a woman hid him under her great hooped dress, where he crouched silently until the constable gave up his search of the premises. Another anecdote of narrow escape tells the tale of Vásquez being hidden in the bed, under the covers, of a newly birthed mother. His friends offered to hide him by letting him crawl under the covers at the foot of the bed while the mother showed off her newborn to the sheriff.
    See also Murrieta, Joaquín
    References Burciaga 1993; Castillo and Camarillo 1973; Greenwood 1966; Jackson 1939; MacLean 1977; Siegal 1994
    Vato Loco (Crazy Dude)
    See Bato
    La Vida Loca (The Crazy Life)
    The dress style of the young men, sometimes called batos locos, usually teenagers, is a Pendleton shirt; perfectly pressed, loose khaki pants; a bright white undershirt; and shiny shoes. The girls, rucas (Indian girls) or cholas (mestizo girls), may wear the same khaki pants or short tight skirts, highly teased long hair, and lots of eye makeup. La vida loca is often romanticized, but it is the hard life of survival in an economically depressed environment and relying on a drug culture and gang members for support.
    See also Bato; Cholos
    References Acosta 1972; Del Fuego 1989; Fregoso 1995; Frias 1982; Mirandé 1985; Rodriguez 1993
    La Vieja Inés y Los Listones (The Old Mother Game)
    A very old game played by little girls that is known by various names. It is called Los Colores (the colors), Los Listones (the ribbons), and Tan Tan. The main players are la mamá and “Saint Inez,” who may also be called La Vieja Inés (Old Lady Inés) or La Virgen Inés (Old Maid Inés). All of the other players are given a color by the mamá: red, yellow, green, blue, or they may choose their own color. La Vieja Inés comes and pretends to knock on the door, Tan, tan. The mother asks, “Quién es?” (Who is it?) and the answer is “La Vieja Inés.” The mother asks, “Que quieres?” (What do you want?). “Quiero colores” is the answer. “Que color quieres?” (What color do you want?) “Quiero verde” (I want green), or any color is mentioned. The little girl whose color is mentioned runs away and La Vieja Inés tries to catch her before she reaches a spot designated as home base. The game goes on until all of the colors have been chosen and all of the girls are caught. In some versions the girls carry ribbons, each of a different color. Scholars who have analyzed the game point to the socialization of gender roles for little girls, and the game serves as a lesson in the inevitable eventual separation from the safety of home. This was one of the games collected by the Federal Writers’ Program in New Mexico during the 1930s. Although there were many games played by Hispano and Mexican children, this one appears to be one with a long historical tradition.
    Jose Limón has written about a version found in Texas. It is an ancient game that can be traced to medieval Spain, to a place called Zafra. In the version from Zafra two teams are involved, one representing evil, the other goodness. One team is led by the devil, el demonio, and the other by an angel, ángel de la guarda (angel of the guard). Each player is named a color, and the two leaders, the devil and the angel, try to gain the most players. In this version it is a battle between good and evil to see who can win the most souls.
    See also Hilitos de Oro; Naranja Dulce
    References Cardozo-Freeman 1975; Ebinger 1993; Limón 1980b; Robe 1972; Writer’s -Program of New Mexico 1976
    La Virgen de Guadalupe
    Also commonly known as Nuestra Señora de Guadalupe, she is the Virgin Mary who appeared to Juan Diego, a Mexican Christian Indian, on December 9, 1531. Historical documents verify the story of her apparitions. She identified herself as the Virgin Mary, the Mother of God, and speaking in Nahuatl, she asked Juan Diego to go to the Spanish bishop and ask that a temple be built there where she appeared, the mount of Tepeyac. To Juan Diego she was a beautiful woman who spoke his language, so after much difficulty he sought to speak to the bishop, but his story was not heard, and he was asked to return another day. The beautiful woman appeared to Juan Diego a second time, and he was asked to seek the bishop’s audience again. On the second try Juan Diego saw the bishop, his story was heard and questioned, but was not believed. The bishop wanted a sign from the Great Lady so that he would know it was really she who was sending Juan Diego. Diego intended to go back to Tepeyac and inform the beautiful woman, but when he returned home he found that his uncle Juan Bernardino was extremely ill. The next morning, on December 12, as he walked to Tlatelolco to call a priest to come to his uncle’s side, the beautiful woman came to him a third time asking what was wrong. Diego told her of his sick uncle and of the request from the bishop. She told him his uncle was now well and would not die and sent him to the top of a hill to cut fresh flowers that he was to take to the bishop as proof of her existence. Diego followed her instructions and at the top of the hill he found beautiful roses of Castile, still covered with dew. He cut them and The Lady, the Mother of God, arranged them in his tilma (cloak) and sent him to the bishop, with the proof requested. When Diego unfolded his tilma in front of the bishop, the roses fell to the floor, and there on the tilma was an image of the Virgin Mary. Now the Spanish bishop believed, and as the beautiful woman requested, a church was built right on the mount of Tepeyac. The tilma with the image of the Virgin Mary still hangs in the temple called Guadalupe. The name that the beautiful Lady gave herself was Tlecuauhtlacupeuh, but to the Spaniards it sounded like Guadalupe, which they instantly recognized as “Our Lady of Guadalupe” from Estremadura, Spain. But the Aztecs understood that in the Nahuatl language the name Tlecuauhtlacupeuh meant “la que viene volando de la luz como el águila de fuego” (she who comes flying from the region of light like an eagle of fire).
    Tonantzin was an Aztec goddess, literally called Our Holy Mother, also known as Tonan. Guadalupe appeared at what was once the temple of Tonantzin at the mount of Tepeyac. Even today in Mexico, La Virgen María is often called Tonantzin. The acceptance of La Virgen de Guadalupe by the indigenous population of Mexico was the beginning of Mexican Christianity and the conversion of the Aztecs to Catholicism. Guadalupe became the symbol of Indian Catholicism, different from the European Catholicism of the Spaniards. As the Aztecs adapted the Catholic religion to their indigenous beliefs, they created a religion that met their own needs and own way of life. She was declared the “Patroness of the Mexican Nation” in 1737, and in 1754 Pope Benedict XIV canonized Guadalupe as an official saint. She was crowned “Queen of Mexico” in 1895, showing how strong a symbol of Mexican nationalism she had become. Today she continues as the country’s strongest symbol of Mexican identity. The cathedral built in her honor can no longer be used because of structural damage, but a new one was built in the early 1970s. Masses are held every hour of the day and the church is constantly filled to capacity.
    Faith in La Virgen de Guadalupe is one of the strongest convictions in Mexican and Chicano culture. Guadalupe has become a powerful cultural image. Her appearance was crucial in restoring dignity and humanity to a conquered people. Eric Wolf refers to Guadalupe as a “master symbol,” “a symbol which seems to enshrine the major hopes and aspirations of an entire society” (34). She is the mother of the mestizo race, La Raza (The People), and a political symbol for the oppressed and powerless. She is affectionately referred to as La Morenita, Virgencita, Lupita, Madrecita, Madre de Dios, and Nuestra Señora. Virgil Elizondo, a Chicano theologian, states, “Guadalupe is the key to understanding the Christianity of the New World and the Christian consciousness of the Mexicans and the Mexican Americans of the United States” (26).
    Belief in her power as a mediator for the oppressed has prompted faithful followers to carry her image into battle for over 400 years. Father Hidalgo, during the Mexican War of Independence; Emiliano Zapata, during the Mexican Revolution; and César Chávez, during his battle for farmworkers’ rights against California agribusiness, all carried the emblem of La Virgen de Guadalupe. The image of Guadalupe provides support for those who believe in her divine power as the deliverer from oppression.
    El Teatro Campesino has created a cultural piece titled La Virgen de Tepeyac (The Virgin of Tepeyac). For many years now it has been performed during the early part of December in the mission church of San Juan Bautista, California. It has become a Bay Area Christmas tradition to make the two-hour journey to the small mission town to experience the miracle of Guadalupe, although all Mexican American churches throughout the United States organize elaborate church ceremonies for December 12, the day of her appearance, so there are literally hundreds of celebrations one can choose from to commemorate the day.
    Contemporary Chicanas continuously look toward Guadalupe and reevaluate her influence in their mothers’ and grandmothers’ lives and in their own lives. Although she is the preeminent representation of womanhood, she has become an icon for women’s subjugation and oppression. In the 1970s the artist Yolanda Lopez created a memorable image of working mothers by painting a garment worker at a sewing machine within the recognizable blue shield background that is easily acknowledged as the emblem of La Virgen de Guadalupe. In New Mexico a young Chicana created a dance theater piece titled Apariciones de la Madre, which incorporated modern ideas of women into the traditional images of the Aztec Guadalupe.
    Chicano muralists have painted images of Guadalupe in her traditional Aztec setting on barrio walls since the late 1960s, and often other cultural symbols, such as a low-rider car, are added to emphasize the Chicano experience. La Virgen de Guadalupe is revered religiously, candles are lit for her, flowers are left at the church for her, and yet she is very much a part of popular culture. Her image is found on T-shirts, key rings, low-rider car hoods, and tattooed across adult male chests. Her face and form are frequently deciphered on tortillas, shadows on walls, and the trunks of trees. When such an image is found, thousands of people, whether in Mexico or the United States, flock to see and pray before the image. The influence of Guadalupe is as powerful today as it was 450 years ago.
    See also El Teatro Campesino
    References Alarcon 1989; Brundage 1979; Demarest and Taylor 1956; Elizondo 1977; -Johnston 1981; Lafaye 1983; Lea 1953; Quirarte 1992; Rodriguez, J., 1994; Vigil 1994, 1998; Wolf 1958

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
    written_2/travel_guides/berlitz1/HandRJerusalem.txt:        includes at least a Continental breakfast. Most West Jerusalem hotels
    written_2/travel_guides/berlitz1/HandRLakeDistrict.txt:        B&B (bed-and-breakfast) rate, per person, with a fee added at many
    written_2/travel_guides/berlitz1/HandRLakeDistrict.txt:        a D, B&B (dinner, bed, and breakfast) rate, which includes the
    written_2/travel_guides/berlitz1/HandRLakeDistrict.txt:        The following price guidelines are for bed and breakfast per
    written_2/travel_guides/berlitz1/HandRLisbon.txt:        breakfast, including service and taxes (currently 5 percent of room
    written_2/travel_guides/berlitz1/HandRLosAngeles.txt:        queen-sized beds. Breakfast is not usually included at US hotels,
    written_2/travel_guides/berlitz1/HandRMadeira.txt:        are for a double room with bath in high season, including breakfast and
    written_2/travel_guides/berlitz1/WhatToEdinburgh.txt:        Salmon and kippers. The kippers you enjoy for breakfast or
    written_2/travel_guides/berlitz1/WhatToIbiza.txt:        Balearic sweet breakfast rolls (ensaimadas) to graixonera, a kind of
    written_2/travel_guides/berlitz1/WhatToIbiza.txt:        •Breakfast, Anyone?
    written_2/travel_guides/berlitz1/WhatToIbiza.txt:        Ibizan breakfast is simply a cup of coffee and a pastry.
    written_2/travel_guides/berlitz1/WhatToIbiza.txt:        and coffee, either with or without eggs. Breakfast coffee (café con
    written_2/travel_guides/berlitz1/WhatToIbiza.txt:        cafés serve breakfast, snacks, coffee, and drinks. Open-air cafés are
    written_2/travel_guides/berlitz1/WhatToIstanbul.txt:        The typical Turkish breakfast, served between 7:00 and
    written_2/travel_guides/berlitz1/WhereToDublin.txt:        serves breakfast and brown-bag lunches. If you want more information
    written_2/travel_guides/berlitz1/WhereToFrance.txt:        with information, brochures, lists of hotels and bed and breakfasts,
    written_2/travel_guides/berlitz1/WhereToItaly.txt:        Make an early start with breakfast (or come back for a late
    written_2/travel_guides/berlitz1/WhereToItaly.txt:        place for breakfast surrounded by 17th- and 18th-century palazzi and
    written_2/travel_guides/berlitz1/WhereToMalaysia.txt:        thousands of moths from the jungle. They make an ideal breakfast for
This command finds every occurence of the word `breakfast` no matter the case of the letters. This could be useful when trying to find a word even when it starts with a captial letter.
