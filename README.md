# R2D2

<head>
    <meta charset="utf-8">
    <title>R2D2</title>

    <!-- Bootstrap 3 -->
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.1.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.1.0/css/bootstrap-theme.min.css">
    <script src="http://code.jquery.com/jquery-1.10.1.min.js"></script>
    <script src="https://netdna.bootstrapcdn.com/bootstrap/3.1.0/js/bootstrap.min.js"></script>
    <style type="text/css" media="screen">
        body {
            padding-top: 80px;
            background-color: #294659;
            color: #CCC;
        }
        #trailer .modal-dialog {
            margin-top: 200px;
            width: 640px;
            height: 480px;
        }
        .hanging-close {
            position: absolute;
            top: -12px;
            right: -12px;
            z-index: 9001;
        }
        #trailer-video {
            width: 100%;
            height: 100%;
        }
        .movie-tile {
            margin-bottom: 20px;
            padding-top: 20px;
        }
        .movie-tile:hover {
            background-color: #444;
            cursor: pointer;
        }
        .movie-tile img {
            box-shadow: 7px 7px 12px #222;
        }
        .scale-media {
            padding-bottom: 56.25%;
            position: relative;
        }
        .scale-media iframe {
            border: none;
            height: 100%;
            position: absolute;
            width: 100%;
            left: 0;
            top: 0;
            background-color: white;
        }
{ 
 background:#202a3f;
}
.container{
    margin-top:8px;
}
.glyphicon-search{
   font-size:20px;
}
.btn-default{
   background:orange;
   width:100px;
   padding:15px;
}
.form-control{
   padding:25px;
   font-size:20px;
}
    </style>
    <script type="text/javascript" charset="utf-8">
        // Pause the video when the modal is closed
        $(document).on('click', '.hanging-close, .modal-backdrop, .modal', function (event) {
            // Remove the src so the player itself gets removed, as this is the only
            // reliable way to ensure the video stops playing in IE
            $("#trailer-video-container").empty();
        });
        // Start playing the video whenever the trailer modal is opened
        $(document).on('click', '.movie-tile', function (event) {
            var trailerYouTubeId = $(this).attr('data-trailer-youtube-id')
            var sourceUrl = 'http://www.youtube.com/embed/' + trailerYouTubeId + '?autoplay=1&html5=1';
            $("#trailer-video-container").empty().append($("<iframe></iframe>", {
              'id': 'trailer-video',
              'type': 'text-html',
              'src': sourceUrl,
              'frameborder': 0
            }));
        });
        // Animate in the movies when the page loads
        $(document).ready(function () {
          $('.movie-tile').hide().first().show("fast", function showNext() {
            $(this).next("div").show("fast", showNext);
          });
        });
    </script>
</head>

<!DOCTYPE html>
<html lang="en">
  <body><div class ="container">
   <form>
    <div class ="input-group">
    <input type="text" class="form-control" placeholder ="search" name="search">
    <div class="input-group-btn">
    <button class="btn btn-default" type="submit">
    <i class="glyphicon glyphicon-search"></i></button>
    </div> 
    </div>
    <!-- Trailer Video Modal -->
    <div class="modal" id="trailer">
      <div class="modal-dialog">
        <div class="modal-content">
          <a href="#" class="hanging-close" data-dismiss="modal" aria-hidden="true">
            <img src="https://lh5.ggpht.com/v4-628SilF0HtHuHdu5EzxD7WRqOrrTIDi_MhEG6_qkNtUK5Wg7KPkofp_VJoF7RS2LhxwEFCO1ICHZlc-o_=s0#w=24&h=24"/>
          </a>
          <div class="scale-media" id="trailer-video-container">
          </div>
        </div>
      </div>
    </div>
    
    <!-- Main Page Content -->
    <div class="container">
      <div class="navbar navbar-inverse navbar-fixed-top" role="navigation">
        <div class="container">
          <div class="navbar-header">
            <a1 class="navbar-brand" href="#">INDIAN BOLLYWOOD IMDB</a1s>
          </div>
        </div>
      </div>
    </div>
    <div class="container">
      
<div class="col-md-6 col-lg-4 movie-tile text-center" data-trailer-youtube-id="y3sBicS_trY" data-toggle="modal" data-target="#trailer">
    <img src="https://upload.wikimedia.org/wikipedia/en/thumb/d/dc/Kabir_Singh.jpg/220px-Kabir_Singh.jpg" width="220" height="342">
    <h2>Kabir singh</h2>
    <p>Kabir Rajdheer Singh is a house surgeon at Delhi Institute of Medical Sciences in Delhi, India. Despite being a brilliant student, he has severe anger management problems that earn the wrath of the dean of the college. Kabir's aggressive nature also earns him a reputation among his juniors as a college bully. After having a brawl alongside his friend Kamal against members of the opposing team during an inter-college football match, the dean asks Kabir to either apologise or leave the college. Kabir initially chooses the latter but stays back after meeting first-year student Preeti Sikka.

Kabir and his friend Shiva enter a third-year classroom and announce that Kabir is in love with Preeti and asserts that she is exclusive to him. Initially afraid, Preeti starts adjusting herself to Kabir's overbearing attitude. She eventually reciprocates his feelings and they develop an intimate relationship. Kabir graduates with an MBBS degree and leaves for Mussoorie to pursue a Master's degree in orthopedic surgery. Over the course of three years, Kabir's and Preeti's relationship becomes stronger. Months later, Kabir visits Preeti's house, where her father sees them kissing and throws Kabir out.

Preeti's father opposes her and Kabir's relationship since he dislikes Kabir's personality. Kabir demands that Preeti must make a decision within six hours otherwise he will end their relationship. By the time she manages to visit Kabir's house, he is drunk, injects morphine into himself, and becomes unconscious for two days. Preeti is then forcibly married to someone from her caste. Kabir learns about the marriage from Shiva and goes to her house in protest. He is assaulted and gets arrested for making a scene. Kabir's father ostracises him from the family home for damaging his reputation.

With Shiva's help, Kabir finds a rented apartment and joins a private hospital as a surgeon. To cope with his emotions, he starts taking drugs, attempts one-night stands, buys a pet dog and names it after Preeti and drinks alcohol; all of which are unsuccessful. Within months, he becomes a successful surgeon and a high-functioning alcoholic who is feared by the hospital's staff members, one of the reasons being his high surgery count. Kabir's self-destructing behaviour and refusal to move on worries Shiva and Kamal. He persuades one of his patients, Jia Sharma, a leading film star, to have a no-strings relationship with him, which he ends when she falls in love with him.

On a day off, Kabir unwillingly agrees to perform a life-saving surgery and collapses with dehydration. The hospital staff examine his blood samples, which show traces of alcohol and cocaine. The hospital chief files a case against Kabir, who accepts the truth on the grounds of violating his professional ethics during an in-house court hearing, despite Shiva making arrangements to bail him out. Kabir's medical license is cancelled for five years and he is evicted from the flat. The next morning, Shiva manages to reach Kabir to convey his grandmother's death; he meets his father, and they reconcile. Kabir gives up his self-destructive habits soon after.

 Preeti reveals that she left her husband days after their marriage and continued to work in a clinic. She tells Kabir that he is the child's father, and they reunite. The pair marries, and Preeti's father apologises for misunderstanding their love for each other.</p>
    <p>Release date: 21 June 2019</p>
</div>

<div class="col-md-6 col-lg-4 movie-tile text-center" data-trailer-youtube-id="03-KVRmd3xo" data-toggle="modal" data-target="#trailer">
    <img src="https://upload.wikimedia.org/wikipedia/en/thumb/1/19/Kedarnath_film_Poster.jpg/220px-Kedarnath_film_Poster.jpg" width="220" height="342">
    <h2>KedarNath</h2>
    <p>In the valley around the Kedarnath temple, Mansoor(Sushant Singh Rajput) is a local Muslim carrying tourists up to the temple. Mukku ( Mandakini ) the daughter of a Hindu Brahmin priest who runs the hostel for pilgrims by the temple on behalf of the temple committee. She is engaged to another Brahmin, nephew of the head priest. He was meant to marry her older sister, but he dumped the sister and switched to her when she grew up to be prettier. And her father agreed. In rebellion (since there is no other way to rebel), Mukku flirts with the local boys and convinces them to come to her house and propose in order to embarrass her father and fiance. However, Mansoor is different, they both notice each other and then Mukku makes the first move and hires him as her regular porter as she goes from her family home to a neighbouring village to help at her uncle’s shop. She talks and talks to him and flirts outrageously and finally gets enough of a reaction to know he feels the same way. They are trapped in the rain together, share stories of their childhood, and then kiss. Her envious sister tells Mansoor that Mukku is just flirting with him as she has flirted with all the other boys. Mukku is unable to defend herself when he confronts her, but starts following him around everywhere, finally sitting in the rain outside his house. Her sister tries to cover for her, but she is found out and her family and the rest of the Brahmin community come for her planning to throw out all the Muslims. Which, not-so-coincidentally, will also open up space for the new luxury hotel they are planning.

Mukku is taken home by her family who move up her wedding. Nevertheless she keeps insisting that Mansoor will come for her. While the Muslim porter community prepares to leave the valley, Mansoor decides not to leave without Mukku. Mukku is married and attempts to commit suicide, however she is saved by her family, her now-husband taunts Mansoor with the news. Mansoor runs to Mukku and promises he will come back for her that night when she is recovered, so they can leave the valley together. Her husband plans to take his band of priests and kill Mansoor and drive out all the Muslims in Hindu deity Shiva’s name. All of a sudden the rains and the floods begin. Mansoor sends his mother with the other porters into the mountains and runs towards Mukku. She and her family are trying to gather the guests of their hostel in a top floor, her husband and his mother arrive driven in by the storm and Mukku refuses to go to him. And then the floor crashes down and her sister and mother are swept away along with half the other people. Mukku and her father and a few others make their way to the temple, Mansoor finds them there just as the water sweeps down. He grabs her hand in the flood, and her father holds on to her and all three are saved. After the water goes down, they make their way to a house that is still standing and wave at an Indian army helicopter that is coming to save them. Mansoor sends up the woman and child who are with them first, then Mukku’s father, then Mukku, and finally prepares to go himself. But there is only space for one more person and the father of the family has not gone yet, so Mansoor sacrifices himself and sends him instead. Three years later, Mukku is still seen living with her father and running the lodge, listening to Mansoor's favourite song on the radio which she dedicated to him and smiles.</p>
    <p>Release date: April 26, 2019</p>
</div>

<div class="col-md-6 col-lg-4 movie-tile text-center" data-trailer-youtube-id="QpvEWVVnICE" data-toggle="modal" data-target="#trailer">
    <img src="https://i.ytimg.com/vi/h8xVG_Qj1g8/maxresdefault.jpg" width="220" height="342">
    <h2>Super 30</h2>
    <p>Super 30 is an upcoming Indian biographical drama film directed by Vikas Bahl, based on the life of mathematician Anand Kumar and his educational program Super 30. The film stars Hrithik Roshan as Kumar and Mrunal Thakur as his wife. The soundtrack is by Ajay-Atul and movie is co-produced by Sajid Nadiadwala. Super 30 will be Phantom Films's last production. The film was shot in Ramnagar Fort and in Sambhar Lake Town which was shown as Kota, Rajasthan. The trailer was released on 4 June 2019, and the film is set to release on 12 July 2019.The first look posters of Hrithik Roshan from Super 30 were unveiled on 5 September 2018 to coincide with the Teacher's Day in India. Second poster with new release date was revealed on 12 January 2019. Another look of Hrithik Roshan from the film unveiled in new poster on 2 June. The next day another poster with Roshan soaking in the rain of success with motto "Misaal Bano, Haqdaar Bano" (Be an example, be qualified) was released. one day later on 4 June official trailer of the film was released by Reliance Entertainment. It garnered 41 million views since its release on YouTube.

The film's producer reported that Hrithik Roshan will be accompanied by Anand Kumar for the promotion of Super 30.

The film is scheduled for theatrical release in India on 12 July 2019, as the release date was advanced by fourteen days.Ajay Atul composed the music for the film and lyrics are written by Amitabh Bhattacharya, making it the second collaboration with Hrithik Roshan after Agneepath and lyrics are written by Amitabh Bhattacharya, making it his sixth collabration with Ajay Atul after My Friend Pinto, Agneepath, Brothers, Dhadak and Thugs of Hindostan.

All tracks written by Amitabh Bhattacharya.The first look posters of Hrithik Roshan from Super 30 were unveiled on 5 September 2018 to coincide with the Teacher's Day in India. Second poster with new release date was revealed on 12 January 2019.Another look of Hrithik Roshan from the film unveiled in new poster on 2 June.The next day another poster with Roshan soaking in the rain of success with motto "Misaal Bano, Haqdaar Bano" (Be an example, be qualified) was released.one day later on 4 June official trailer of the film was released by Reliance Entertainment. It garnered 41 million views since its release on YouTube.

The film's producer reported that Hrithik Roshan will be accompanied by Anand Kumar for the promotion of Super 30.[28]

The film is scheduled for theatrical release in India on 12 July 2019, as the release date was advanced by fourteen days.Mathematician Anand Kumar today expressed great pleasure over look of superstar Hrithik Roshan in the biopic made on him which almost matches his appearance during university days.

Kumar lauded the first look of the biopic being made on him which has been shared on the social media by cine actor Hrithik Roshan who plays the Super 30 founder in the Bollywood movie being directed by national award winner Vikas Bahl.

"I was delighted and pleasantly surprised to see the first look wherein Hrithik sports a rugged, bearded look. I had been told that at present the shooting was being done of my college days. I took out an old photograph of mine, of the time when I was studying at Patna University. I found the resemblance to be uncanny", Kumar told PTI.</p>
    <p>Release date: July 5, 2019</p>
</div>

<div class="col-md-6 col-lg-4 movie-tile text-center" data-trailer-youtube-id="Gioj99SDUtA" data-toggle="modal" data-target="#trailer">
    <img src="https://i.ytimg.com/vi/HKOJY0cU63E/maxresdefault.jpg" width="220" height="342">
    <h2>Article 15</h2>
    <p>Article 15 is a 2019 Indian crime drama filmdirected by Anubhav Sinha and produced jointly by Zee Studios and Benaras Media Works. Written by Gaurav Solanki and Anubhav Sinha, it stars Ayushmann Khurrana, Isha Talwar, Sayani Gupta, Kumud Mishra, Manoj Pahwa, Veen and Sumbul Touqeer.

The film is based on Article 15 of the Indian Constitution, which prohibits discrimination on grounds of religion, race, caste, sex or place of birth.While not based on one specific event, the film is inspired by multiple true life events including 2014 Badaun gang rape allegations and 2016 Una flogging incident. Filming began on 1 March 2019 in Lucknow.The film follows a police investigation that commences after three teenage girls go missing from a small village.
It was selected as the opening film for the 10th edition of London Indian Film Festival to be premiered on 20 June. Article 15 released theatrically on 28 June 2019 and received critically acclaimed reviews from critics.[11] On review aggregator website Rotten Tomatoes, the film holds a rating of 93% based on fifteen reviews.Sreeparna Sengupta of The Times of India gave the film 4/5 stars, praising performance of Ayushmann Khurrana, Manoj Pahwa, Kumud Mishra and Mohammed Zeeshan Ayyub, and background music and cinematography of Ewan Mulligan as well. She felt that Sinha had given another dimension to narrative by surfacing the artful shades through the characters and setting. She opines, "Anubhav Sinha’s Article 15 is designed like a crime thriller. What works for the film is that it’s thought provoking, hard hitting while unflinchingly bringing to light burning social issues." Concluding, she wrote that the film is not a 'light watch', rather it is 'definitely relevant', 'compelling' and will start a debate.Devesh Sharma reviewing for Filmfare rates the film with 4/5 stars. He praised screenplay, dialogues and cinematography of the film apart from performance of Khurrana and supporting cast. He recommends watching the film for its 'riveting performances' and its 'underlying message', and opines that the film presents the candid truth about the contemporary society. Quoting Jack Nicholson’s character from A Few Good Men -- “You can’t handle the truth” he hopes that the audience goes out to watch the film and 'learns to handle the truth...'[32] Priyanka Sinha Jha of CNN-News18, praising Khurrana and ensemble of Kumud Sharma, Manoj Pahwa, Sayani Gupta, Mohammed Zeeshan Ayyub, and M Nassar for their performances, rates the film with 4/5 stars. Agreeing with Vetticad she writes, "Article 15 is remarkable in that it does not pontificate. It merely holds up the mirror to a society still entangled in age-old caste politics that absolutely overrides the modern ideals of liberty and equality." Concluding, she opines that Sinha has knack of combining elements of popular film-making with realistic story-telling to give masterful films.[33] Writing for the NDTV Saibal Chatterjee, termed it a 'radical' film,</p>
    <p>Release date: June 7, 2019</p>
</div>

<div class="col-md-6 col-lg-4 movie-tile text-center" data-trailer-youtube-id="QrxOdxG1x40" data-toggle="modal" data-target="#trailer">
    <img src="https://upload.wikimedia.org/wikipedia/en/thumb/c/c9/Bharat_film_poster.jpg/220px-Bharat_film_poster.jpg" width="220" height="342">
    <h2>Bharat</h2>
    <p>Bharat  is a 2019 Indian Hindi-language action drama film[5][6] written and directed by Ali Abbas Zafar. It is jointly produced by Atul Agnihotri, Alvira Khan Agnihotri, Bhushan Kumar, Krishan Kumar, Nikhil Namit and Salman Khan under the banners Reel Life Productions, Salman Khan Films and T-Series. The film stars Salman Khan, Katrina Kaif, Tabu, Sunil Grover, Disha Patani and Jackie Shroff. It traces India's post-independence history from the perspective of a common man, and follows his life from the age of 18 to 70.

Based on the 2014 South Korean film Ode to My Father, principal photography for Bharat began in April 2018. Shooting took place at such locations as Abu Dhabi, Spain, Malta, Punjab and Delhi. Kaif joined the cast soon after Priyanka Chopra opted out of the role after filming commenced, for her impending engagement to Nick Jonas. Filming concluded in March 2019. The film's soundtrack was composed by Vishal-Shekhar, with lyrics written by Irshad Kamil, and released under the banner T-Series.

Bharat was theatrically released in India on 5 June 2019, on the occasion of Eid al-Fitr. It received mixed reviews from critics, with praise directed to Kaif's performance, while the pace, Zafar's adaptation and screenplay received criticism. The film earned Rs 42.30 crore on its first day, becoming Khan's biggest opening day release.Bharat became the 2nd highest grossing Bollywood film of 2019 in the opening week.During the 1947 Partition of India, Gautam Kumar and his family board a train to India with thousands of refugees to save themselves from the terrible riots. In the chaos, Gautam's young son, Bharat (then 8 years old), accidentally loses his baby sister, Gudiya. Gautam stays behind to search for her, despite knowing the risk, and tells his son to take his mother and two younger siblings to Bharat's aunt's imported goods store. Before letting go, Gautam has Bharat promise him that Bharat will keep the family together in his place.

As a child, Bharat takes all sorts of odd jobs to support his family. In 1964, as a pre-teen, he joins The Great Russian Circus with his best friend, Vilayati, and spends a number of years there, becoming one of the biggest attractions of the show, and also wooing Radha in the process. He leaves the circus when his brother Chote hurts himself in an accident while trying to emulate him.

In the mid-1970s, Bharat joins the Indian migration prompted by the discovery of oil in the Gulf region, as he hopes to earn enough to send back home. Here, he falls in love with his chief engineer Kumud Raina (Katrina) and survives a mining accident. Kumud confesses her love for him, but he tells Kumud he can't marry her, as he is afraid such a commitment will come in the way of fulfilling his father's promise, and leaves Saudi Arabia after his visa expires. Back home in India, Kumud arrives during his sister's wedding to announce their love, and says she is okay with being in a relationship without marriage. Bharat's mother agrees on Bharat's wish that they can be in a live-in relationship.</p>
    <p>Release date: April 5, 2019</p>
</div>

<div class="col-md-6 col-lg-4 movie-tile text-center" data-trailer-youtube-id="" data-toggle="modal" data-target="#trailer">
    <img src="https://upload.wikimedia.org/wikipedia/en/thumb/0/0e/Baazaar_-_Poster.jpg/220px-Baazaar_-_Poster.jpg" width="220" height="342">
    <h2>Bazaar</h2>
    <p>Allahabad stock trader Rizwan Ahmed arrives in Mumbai through a flight. He is determined to work with his hero, Gujarati financial maven Shakun Kothari (Saif Ali Khan). Rizwan bluffs his way into the city's largest trading firm and manages to convince them to give him a job. He ropes in a high-profile client and with the help of his co-worker and girlfriend Priya (Radhika Apte), he begins a successful career at the firm. When attending an event with Priya, he spots Shakun Kothari and gives stock advice that turns out to be correct. Kothari then hires him as his broker, warning that he can never lose him any money. After his first trade with Kothari's funds ends badly, Rizwan is desperate not to lose Kothari's account and illegally uses insider information from Priya to recoup Kothari's losses. Rizwan becomes close to Kothari and his wife Mandira (Chitrangda Singh), visiting Kothari's lavish home and relaxing on his yacht with Priya. Meanwhile, Kothari offers Rizwan a chance to make even more money when he learns that the government is going to begin accepting bids from telecommunications companies for a new project. Kothari informs Rizwan that he has bribed a government minister to select a company called Skycom and the two can make a killing on the deal. Kothari gives Rizwan the money to buy Skycom and Rizwan becomes the company's owner. He also convinces his new brother-in-law Anwar to invest all of his savings to Skycom shares. However, Skycom's bid is rejected, and Rizwan is ruined when Kothari sells off all of his Skycom shares right before the announcement of the bid winner. Rizwan discovers that Kothari deliberately set him up to take the fall for Skycom for Kothari's own personal monetary profit and that he arranged for Priya to influence him from the beginning. SEBI agents detain Rizwan for insider trading, but their real target is Kothari. Using information from Kothari's wife, Rizwan is able to prove that Kothari has been bribing government ministers with diamonds. Shakun is arrested and his wife and kids leave him. After the numerous court hearings, Shakun is summoned as Priya gives in as witness to the bribes. Rizwan questions her that why did she surender herself since Rizwan did not reveal her name, she leaves Rizwan, saying she deserves this. Shakun comes out on bail after a month and returns to his empty house, with his wife and kids gone. He calls his secretary and tells him, that the "market" is open, returning to his deeds.</p>
    <p>Release date: June 26, 2019</p>
</div>

    </div>
  </body>
</html>
