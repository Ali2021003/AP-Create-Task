var x = getWidth() / 10;
var y = getHeight() / 3.5;
function start(){
    startingScreen();
    var startingQuestion = readLine("What do you want to learn about? Countries or States?");
    if (startingQuestion == "Countries"){
        countryFacts();
    }
    if (startingQuestion == "States"){
        stateFacts();
    }
}
function countryFacts(){
    var countryQuestion = readLine("What country do you want to learn about it? ");
    if (countryQuestion == "Brazil"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/transcoded/0/0d/Hino-Nacional-Brasil-instrumental-mec.ogg/Hino-Nacional-Brasil-instrumental-mec.ogg.mp3");
        printFacts("Brazil shares a border with all South American countries except for Chile and Ecuador.");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/en/0/05/Flag_of_Brazil.svg");
        sizeArea("1.3 Million Sq Mi");
    }
    if (countryQuestion == "France"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/3/30/La_Marseillaise.ogg");
        printFacts("France technically stretches out over 12 different time zones");
        sizeArea("210 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/en/c/c3/Flag_of_France.svg");
    }
    if (countryQuestion == "Rwanda"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/transcoded/0/0e/Hymne_National_du_Rwanda.ogg/Hymne_National_du_Rwanda.ogg.mp3");
        printFacts("The plastic bags have been banned");
        sizeArea("10 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/1/17/Flag_of_Rwanda.svg");
    }
    if (countryQuestion == "Venezuala"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/f/f0/United_States_Navy_Band_-_Gloria_al_Bravo_Pueblo.ogg");
        printFacts("It has the second largest oil reserves after Saudi Arabia");
        sizeArea("340 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/7/7b/Flag_of_Venezuela_%28state%29.svg");
    }
    if (countryQuestion == "Liberia"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/6/65/Liberia_National_Anthem.ogg");
        printFacts("Liberia has never been colonized and it was created for free black slaves");
        sizeArea("21 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/b/b8/Flag_of_Liberia.svg");
    }
    if (countryQuestion == "China"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/b/b9/March_of_the_Volunteers_instrumental.ogg");
        printFacts("Many Chinese emperors thought to be ancestors of dragons");
        sizeArea("3.7 Million Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/f/fa/Flag_of_the_People%27s_Republic_of_China.svg");
    }
    if (countryQuestion == "Finland"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/6/61/United_States_Navy_Band_-_Maamme.ogg");
        printFacts("In Finnish, they call Finland 'Suomi'");
        sizeArea("134 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/b/bc/Flag_of_Finland.svg");
    } 
    if (countryQuestion == "Iran"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/transcoded/f/f2/Sorud-e_Mell%C3%AD-e_Yomhur%C3%AD-e_Eslam%C3%AD-e_Ir%C3%A1n_%28instrumental%29.oga/Sorud-e_Mell%C3%AD-e_Yomhur%C3%AD-e_Eslam%C3%AD-e_Ir%C3%A1n_%28instrumental%29.oga.mp3");
        printFacts("It's the only theocratic country under Shia Islam");
        sizeArea("636 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/c/ca/Flag_of_Iran.svg");
    }
    if (countryQuestion == "Canada"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/transcoded/2/2c/%22O_Canada%22%2C_performed_by_the_United_States_Third_Marine_Aircraft_Wing_Band.oga/%22O_Canada%22%2C_performed_by_the_United_States_Third_Marine_Aircraft_Wing_Band.oga.mp3");
        printFacts("It has the most lakes out of any country");
        sizeArea("3.8 Million Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/d/d9/Flag_of_Canada_%28Pantone%29.svg");
    }
    if (countryQuestion == "Poland"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/b/b1/Mazurek_Dabrowskiego.ogg");
        printFacts("It's national symbol is a white eagle");
        sizeArea("121 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/en/1/12/Flag_of_Poland.svg");
    }
    if (countryQuestion == "Bosnia and Herzegovina"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/en/transcoded/d/dd/Bosnia_and_Herzegovina%27s_national_anthem.ogg/Bosnia_and_Herzegovina%27s_national_anthem.ogg.mp3");
        printFacts("It has 3 Presidents");
        sizeArea("35 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/b/bf/Flag_of_Bosnia_and_Herzegovina.svg");
    }
    if (countryQuestion == "Mexico"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/9/9d/Himno_Nacional_Mexicano_instrumental.ogg");
        printFacts("The largest source of immigration into the USA is Mexico");
        sizeArea("758 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/f/fc/Flag_of_Mexico.svg");
    }
    if (countryQuestion == "Italy"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/transcoded/c/c0/National_anthem_of_Italy_-_U.S._Navy_Band_%28long_version%29.ogg/National_anthem_of_Italy_-_U.S._Navy_Band_%28long_version%29.ogg.mp3");
        printFacts("Italy was the birthplace of the Renaissance");
        sizeArea("116 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/en/0/03/Flag_of_Italy.svg");
    }
    if (countryQuestion == "Botswana"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/c/cb/United_States_Navy_Band_-_Fatshe_leno_la_rona.ogg");
        printFacts("It is the least corrupt country in Africa");
        sizeArea("225 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/f/fa/Flag_of_Botswana.svg");
    }
    if (countryQuestion == "Madagascar"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/d/dd/Ry_Tanindrazanay_malala_%C3%B4%21_%28instrumental%29.ogg");
        printFacts("It was first inhabited by people of Asian descent not African");
        sizeArea("227 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/b/bc/Flag_of_Madagascar.svg");
    }
    if (countryQuestion == "Somalia"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/transcoded/4/4e/Somali_national_anthem%2C_performed_by_the_United_States_Navy_Band.oga/Somali_national_anthem%2C_performed_by_the_United_States_Navy_Band.oga.mp3");
        printFacts("It is one of the 8 countries that lies on the Equator");
        sizeArea("246 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/a/a0/Flag_of_Somalia.svg");
    }
    if (countryQuestion == "South Africa"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/1/1d/South_African_national_anthem.oga");
        printFacts("It has the largest concentration of whites out of all countries");
        sizeArea("471 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/a/af/Flag_of_South_Africa.svg");
    }
    if (countryQuestion == "Algeria"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/transcoded/7/79/National_anthem_of_Algeria%2C_by_the_U.S._Navy_Band.oga/National_anthem_of_Algeria%2C_by_the_U.S._Navy_Band.oga.mp3");
        printFacts("It is the largest country in Africa");
        sizeArea("916 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/7/77/Flag_of_Algeria.svg");
    }
    if (countryQuestion == "Russia"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/transcoded/4/41/National_Anthem_of_Russia_%282000%29%2C_instrumental%2C_one_verse.ogg/National_Anthem_of_Russia_%282000%29%2C_instrumental%2C_one_verse.ogg.mp3");
        printFacts("It is larger than the dwarf planet Pluto");
        sizeArea("6.6 Million Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/en/f/f3/Flag_of_Russia.svg");
    }
    if (countryQuestion == "USA"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/transcoded/6/65/Star_Spangled_Banner_instrumental.ogg/Star_Spangled_Banner_instrumental.ogg.mp3");
        printFacts("About 1 in every 39 Americans live in New York");
        sizeArea("3.8 Million Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/en/a/a4/Flag_of_the_United_States.svg");
    }
    if (countryQuestion == "Lesotho"){
        nationalAnthem("https://upload.wikimedia.org/wikipedia/commons/transcoded/a/aa/National_anthem_of_Lesotho%2C_performed_by_the_U.S._Navy_Band.wav/National_anthem_of_Lesotho%2C_performed_by_the_U.S._Navy_Band.wav.ogg");
        printFacts("It doesn't have one single code of law");
        sizeArea("30 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/thumb/4/4a/Flag_of_Lesotho.svg/125px-Flag_of_Lesotho.svg.png");
    }
}
function stateFacts(){
    wholeScreenMap("https://contestimg.wish.com/api/webimage/5b6be4bcabae25279b7826e9-large.jpg");
    var stateQuestion = readLine("What state do you want to learn about? ");
    if(stateQuestion == "Alabama"){
        printFacts("It's nickname is the Yellow Hammer State");
        sizeArea("52 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/Flag_of_Alabama.svg/600px-Flag_of_Alabama.svg.png");
    }
    if(stateQuestion == "Alaska"){
        printFacts("It's capital, Juneau, is not accessible to the rest of the state by road or train tracks");
        sizeArea("663 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/e/e6/Flag_of_Alaska.svg");
    }
    if(stateQuestion == "Arizona"){
        printFacts("In Phoenix, throughout the year, the temperature can vary from 7 degrees to 106");
        sizeArea("114 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/thumb/9/9d/Flag_of_Arizona.svg/250px-Flag_of_Arizona.png");
    }
    if(stateQuestion == "Arkansas"){
        printFacts("It's name derives from Osage");
        sizeArea("53 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/thumb/9/9d/Flag_of_Arkansas.svg/250px-Flag_of_Arkansas.svg.png");
    }
    if(stateQuestion == "California"){
        printFacts("California has a bigger population than Canada");
        sizeArea("156 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/thumb/0/01/Flag_of_California.svg/250px-Flag_of_California.svg.png");
    }
    if(stateQuestion == "Colorado"){
        printFacts("Minimum wage is $11.10 per hour");
        sizeArea("103 Thousand Sq Mi");
        flagImage(x,y,"https://statesymbolsusa.org/sites/statesymbolsusa.org/files/primary-images/flagofColoradoCO.jpg");
    }
    if(stateQuestion == "Connecticut"){
        printFacts("It never ratified the 18th Amendment");
        sizeArea("5 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/thumb/9/96/Flag_of_Connecticut.svg/250px-Flag_of_Connecticut.png");
    }
    if(stateQuestion == "Delaware"){
        printFacts("It has only 3 counties in the entire state");
        sizeArea("2 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/thumb/c/c6/Flag_of_Delaware.svg/250px-Flag_of_Delaware.png");
    }
    if(stateQuestion == "Florida"){
        printFacts("It is the flattest state, even flatter than Kansas");
        sizeArea("66 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/thumb/f/f7/Flag_of_Florida.svg/250px-Flag_of_Florida.png");
    }
    if(stateQuestion == "Georgia"){
        printFacts("One of the original 13 colonies and 7 Confederate States");
        sizeArea("58 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/thumb/5/54/Flag_of_Georgia_%28U.S._state%29.svg/125px-Flag_of_Georgia_%28U.S._state%29.png");
    }
    if(stateQuestion == "Hawaii"){
        printFacts("It's the only state that can produce coffee");
        sizeArea("1.5 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/Flag_of_Hawaii.svg/250px-Flag_of_Hawaii.svg.png");
    }
    if(stateQuestion == "Idaho"){
        printFacts("1 in 5 people in Idaho is Mormon");
        sizeArea("84 Thousand Sq Mi");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Flag_of_Idaho.svg/250px-Flag_of_Idaho.svg.png");;
    }
    if(stateQuestion == "Illinois"){
        printFacts("The capital is Springfield, not Chicago");
        flagImage(x,y,"https://upload.wikimedia.org/wikipedia/commons/thumb/0/01/Flag_of_Illinois.svg/125px-Flag_of_Illinois.svg.png");
    }
}
function printFacts(x){
    println(x);
}    
function sizeArea(y){
    println(y);
}
function flagImage(a,b,url){
    var flagImage = new WebImage(url);
    flagImage.setSize(230,163);
    flagImage.setPosition(a + 40, b +5);
    add(flagImage);
}
function startingScreen(){
    var worldMap = new WebImage("https://www.mapsnworld.com/world-wall-map.jpg");
    worldMap.setSize(getWidth(),getHeight());
    worldMap.setPosition(0,0);
    add(worldMap);
}
/* Below function is supposed to display maps of continents and countries, but 
this will all be a backup function */ 
function wholeScreenMap(url){
    var wholeScreenMap = new WebImage(url);
    wholeScreenMap.setSize(getWidth(),getHeight());
    wholeScreenMap.setPosition(0,0);
    add(wholeScreenMap);
}
function nationalAnthem(url){
    var mySong = new Audio(url);
    mySong.play();
    
}