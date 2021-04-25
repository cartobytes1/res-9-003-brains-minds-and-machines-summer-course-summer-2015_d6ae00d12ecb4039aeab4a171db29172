---
about_this_resource_text: "<p><strong>Description:</strong> Neural networks in the\
  \ brain continually adapt their form and function to changing circumstances. Nick\
  \ Cheney explores how this neuroplasticity can be modeled in deep learning networks,\
  \ yielding stable learning behavior in dynamically changing networks.</p>\r\n<p><strong>Speaker:</strong>\
  \ Nick Cheney</p>"
course_id: res-9-003-brains-minds-and-machines-summer-course-summer-2015
embedded_media:
- id: Video-YouTube-Stream
  media_location: _qTVDxXBK5A
  parent_uid: 48effe198a4cdae5a0f4f070d0d2025f
  title: Video-YouTube-Stream
  type: Video
  uid: 08f259f9ac4d1be705cf6b47a018bb85
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/_qTVDxXBK5A/default.jpg
  parent_uid: 48effe198a4cdae5a0f4f070d0d2025f
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 83fff12db5c8431119156c157c548859
- id: 3Play-3PlayYouTubeid-MP4
  media_location: _qTVDxXBK5A
  parent_uid: 48effe198a4cdae5a0f4f070d0d2025f
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 25f5b33b4f86a3363b423be957161074
- id: qTVDxXBK5A.srt
  parent_uid: 48effe198a4cdae5a0f4f070d0d2025f
  technical_location: https://ocw.mit.edu/resources/res-9-003-brains-minds-and-machines-summer-course-summer-2015/projects/nick-cheney-capturing-neural-plasticity-in-deep-networks/qTVDxXBK5A.srt
  title: 3play caption file
  type: null
  uid: d09a4899416d00b989a2db013b9eb58e
- id: qTVDxXBK5A.pdf
  parent_uid: 48effe198a4cdae5a0f4f070d0d2025f
  technical_location: https://ocw.mit.edu/resources/res-9-003-brains-minds-and-machines-summer-course-summer-2015/projects/nick-cheney-capturing-neural-plasticity-in-deep-networks/qTVDxXBK5A.pdf
  title: 3play pdf file
  type: null
  uid: b3d043364a938e1646d808a0d7eaea49
- id: Caption-3Play YouTube id-SRT
  parent_uid: 48effe198a4cdae5a0f4f070d0d2025f
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 1dccfec9729bd48d8e1c906f8bc6ac83
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 48effe198a4cdae5a0f4f070d0d2025f
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 4eba699b36009c9d2bcf87da057dac4c
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MITRES.9-003SU15/MITRES9_003SU15_Project_2_300k.mp4
  parent_uid: 48effe198a4cdae5a0f4f070d0d2025f
  title: Video-Internet Archive-MP4
  type: Video
  uid: 7514f2381e65c0bfc31dfe517301d772
inline_embed_id: 33470588nickcheneycapturingneuralplasticityindeepnetworks58187734
layout: video
order_index: null
parent_uid: 5a9d01c0741d24bb27ad5970bde6ab28
related_resources_text: ''
short_url: nick-cheney-capturing-neural-plasticity-in-deep-networks
technical_location: https://ocw.mit.edu/resources/res-9-003-brains-minds-and-machines-summer-course-summer-2015/projects/nick-cheney-capturing-neural-plasticity-in-deep-networks
template_type: Tabbed
title: 'Nick Cheney: Capturing Neural Plasticity in Deep Networks'
transcript: <p><span m='9740'>NICK CHENEY:</span> <span m='10240'>I'm</span> <span
  m='10480'>Nick</span> <span m='10630'>Cheney.</span> <span m='11340'>I'm</span>
  <span m='11500'>finishing</span> <span m='11890'>my</span> <span m='12100'>PhD</span>
  <span m='12730'>in</span> <span m='12850'>Computational</span> <span m='13540'>Biology</span>
  <span m='14110'>at</span> <span m='14230'>Cornell</span> <span m='14590'>University.</span>
  <span m='15460'>Gabriel</span> <span m='16180'>Kreiman</span> <span m='16500'>and</span>
  <span m='16720'>I</span> <span m='17260'>are</span> <span m='17590'>interested</span>
  <span m='18670'>in</span> <span m='19690'>seeing</span> <span m='20050'>how</span>
  <span m='20620'>deep</span> <span m='20830'>networks</span> <span m='21370'>respond</span>
  <span m='21910'>to</span> <span m='22120'>neuroplasticity.</span> <span m='23580'>So</span>
  <span m='23740'>in</span> <span m='23830'>the</span> <span m='23920'>brain,</span>
  <span m='24320'>we</span> <span m='24420'>know</span> <span m='24520'>that</span>
  <span m='25330'>the</span> <span m='25450'>brain</span> <span m='25660'>is</span>
  <span m='25750'>constantly</span> <span m='26320'>in</span> <span m='26410'>flux.</span>
  <span m='27070'>And</span> <span m='27910'>neurons</span> <span m='28480'>are</span>
  <span m='28990'>growing</span> <span m='29500'>and</span> <span m='29590'>dying.</span>
  <span m='30280'>Weights</span> <span m='30610'>are</span> <span m='30700'>changing</span>
  <span m='31120'>in</span> <span m='31180'>response</span> <span m='31600'>to</span>
  <span m='31720'>stimuli.</span> <span m='32439'>But</span> <span m='32680'>most</span>
  <span m='32900'>of</span> <span m='32940'>the</span> <span m='33010'>time,</span>
  <span m='33250'>machine</span> <span m='33550'>learning,</span> <span m='33820'>what</span>
  <span m='33970'>we</span> <span m='34090'>do</span> <span m='34480'>is</span> <span
  m='35350'>pre-train a</span> <span m='35840'>network</span> <span m='36310'>on</span>
  <span m='37330'>some</span> <span m='37540'>training</span> <span m='37870'>set.</span>
  <span m='38150'>But</span> <span m='38170'>then</span> <span m='38290'>we</span>
  <span m='38350'>want</span> <span m='38530'>to</span> <span m='38590'>use</span>
  <span m='38740'>it</span> <span m='38790'>for</span> <span m='38910'>real--</span>
  <span m='39160'>we</span> <span m='39280'>freeze</span> <span m='39670'>it</span>
  <span m='40720'>and</span> <span m='41080'>keep</span> <span m='41260'>it</span>
  <span m='41350'>in</span> <span m='41440'>some</span> <span m='41620'>static</span>
  <span m='42010'>form.</span> </p><p><span m='42910'>There's</span> <span m='43300'>been</span>
  <span m='43480'>a</span> <span m='43510'>lot</span> <span m='43660'>more</span>
  <span m='43840'>emphasis</span> <span m='44200'>lately</span> <span m='44560'>on</span>
  <span m='44740'>more</span> <span m='44980'>online</span> <span m='45430'>learning</span>
  <span m='46150'>so</span> <span m='46330'>that</span> <span m='46450'>you</span>
  <span m='46600'>learn</span> <span m='47050'>as</span> <span m='47320'>you're</span>
  <span m='47500'>working</span> <span m='47860'>on</span> <span m='48010'>a</span>
  <span m='48110'>data</span> <span m='48560'>set.</span> <span m='48970'>And</span>
  <span m='50280'>in</span> <span m='50410'>those</span> <span m='50560'>kind</span>
  <span m='50710'>of</span> <span m='50800'>environments,</span> <span m='51280'>we</span>
  <span m='51370'>think</span> <span m='51640'>that</span> <span m='52330'>the</span>
  <span m='52420'>network</span> <span m='52760'>will</span> <span m='52870'>be</span>
  <span m='52990'>changing</span> <span m='53380'>quite</span> <span m='53620'>a</span>
  <span m='53650'>bit.</span> <span m='53960'>So</span> <span m='54010'>we're</span>
  <span m='54160'>looking</span> <span m='54520'>at</span> <span m='54760'>how</span>
  <span m='56380'>that</span> <span m='56530'>network</span> <span m='56890'>could</span>
  <span m='57010'>be</span> <span m='57190'>robust</span> <span m='57640'>to</span>
  <span m='57730'>those</span> <span m='57910'>kind</span> <span m='58090'>of</span>
  <span m='58150'>changes</span> <span m='59380'>much</span> <span m='59650'>like</span>
  <span m='59830'>the</span> <span m='59920'>brain</span> <span m='60220'>is</span>
  <span m='60540'>to</span> <span m='61295'>every day</span> <span m='61730'>stimuli</span>
  <span m='62025'>and</span> <span m='62320'>actions</span> <span m='62800'>it</span>
  <span m='63160'>sees.</span> <span m='63640'>To</span> <span m='63760'>start</span>
  <span m='64120'>out</span> <span m='65150'>just</span> <span m='65440'>doing</span>
  <span m='65830'>a</span> <span m='66220'>very</span> <span m='66670'>simple</span>
  <span m='67210'>test</span> <span m='67990'>looking</span> <span m='68350'>at</span>
  <span m='68770'>perturbations</span> <span m='69640'>of</span> <span m='69820'>the</span>
  <span m='69910'>network.</span> </p><p><span m='70460'>So</span> <span m='70720'>just</span>
  <span m='70930'>throwing</span> <span m='71350'>random</span> <span m='71710'>changes</span>
  <span m='72190'>at</span> <span m='72340'>the</span> <span m='72460'>weights</span>
  <span m='74110'>that</span> <span m='74320'>make</span> <span m='74620'>up</span>
  <span m='74770'>this</span> <span m='74920'>network</span> <span m='76120'>and</span>
  <span m='76210'>seeing</span> <span m='76480'>how</span> <span m='76660'>that</span>
  <span m='76810'>affects</span> <span m='77110'>its</span> <span m='77230'>ability</span>
  <span m='77590'>to</span> <span m='77710'>classify</span> <span m='78550'>images.</span>
  <span m='79690'>After</span> <span m='79990'>that,</span> <span m='80200'>we're</span>
  <span m='80350'>looking</span> <span m='80710'>at</span> <span m='81700'>how</span>
  <span m='81910'>different</span> <span m='82420'>parts</span> <span m='83020'>of</span>
  <span m='83260'>the</span> <span m='83350'>network</span> <span m='83740'>respond</span>
  <span m='84340'>differently</span> <span m='84970'>to</span> <span m='85480'>these</span>
  <span m='85660'>kind</span> <span m='85840'>of</span> <span m='85900'>changes.</span>
  <span m='86920'>And</span> <span m='87100'>then,</span> <span m='87340'>ideally,</span>
  <span m='87730'>we'd</span> <span m='87910'>like</span> <span m='88090'>to</span>
  <span m='88210'>have</span> <span m='88450'>some</span> <span m='88690'>kind</span>
  <span m='88870'>of</span> <span m='88960'>rule</span> <span m='89350'>that</span>
  <span m='90340'>doesn't</span> <span m='90670'>affect</span> <span m='91090'>the</span>
  <span m='91540'>performance</span> <span m='92020'>of</span> <span m='92080'>the</span>
  <span m='92170'>network</span> <span m='92500'>that</span> <span m='92650'>much</span>
  <span m='92900'>and</span> <span m='92980'>it's</span> <span m='93130'>able</span>
  <span m='93400'>to</span> <span m='94330'>maintain</span> <span m='94930'>its</span>
  <span m='95080'>ability</span> <span m='95440'>to</span> <span m='95530'>classify</span>
  <span m='96490'>throughout</span> <span m='96940'>seeing</span> <span m='97260'>a</span>
  <span m='97330'>number</span> <span m='97540'>of</span> <span m='97630'>stimuli.</span>
  </p><p><span m='98480'>So</span> <span m='98560'>we</span> <span m='98710'>know</span>
  <span m='98890'>that</span> <span m='99520'>the</span> <span m='99640'>brain</span>
  <span m='99940'>has</span> <span m='100150'>certain</span> <span m='100420'>learning</span>
  <span m='100720'>rules</span> <span m='101380'>like</span> <span m='101780'>Hebb's
  rule,</span> <span m='103720'>in</span> <span m='103840'>which</span> <span m='104560'>neurons</span>
  <span m='105080'>that</span> <span m='105610'>fire</span> <span m='106000'>one</span>
  <span m='106210'>after</span> <span m='106510'>another</span> <span m='106870'>end</span>
  <span m='107000'>up</span> <span m='107110'>strengthening</span> <span m='107590'>their</span>
  <span m='107740'>connections</span> <span m='108310'>or</span> <span m='109630'>conversely</span>
  <span m='110320'>weakening</span> <span m='110710'>their</span> <span m='111100'>reactions.</span>
  <span m='112030'>Then</span> <span m='112240'>we're</span> <span m='112360'>soon</span>
  <span m='112570'>going</span> <span m='112690'>to</span> <span m='112750'>see</span>
  <span m='112930'>if</span> <span m='113170'>rules</span> <span m='113530'>like</span>
  <span m='113770'>that</span> <span m='114970'>end</span> <span m='115180'>up</span>
  <span m='115480'>providing</span> <span m='116080'>stable</span> <span m='116830'>perturbations</span>
  <span m='117580'>where</span> <span m='117790'>the</span> <span m='118120'>network</span>
  <span m='118450'>can</span> <span m='118570'>easily</span> <span m='118900'>recover</span>
  <span m='120700'>and</span> <span m='120790'>maintain</span> <span m='121240'>what</span>
  <span m='121390'>it's</span> <span m='121510'>doing</span> <span m='121810'>or</span>
  <span m='122020'>unstable</span> <span m='122530'>ones</span> <span m='122860'>where</span>
  <span m='123100'>we're</span> <span m='123250'>going</span> <span m='123400'>to</span>
  <span m='123850'>go</span> <span m='124030'>down</span> <span m='124300'>on</span>
  <span m='124420'>track.</span> </p><p><span m='125340'>Or</span> <span m='125440'>we</span>
  <span m='125560'>know</span> <span m='125740'>that</span> <span m='125850'>deep</span>
  <span m='126070'>networks</span> <span m='126670'>act</span> <span m='127720'>similar</span>
  <span m='128229'>to</span> <span m='128350'>how</span> <span m='128500'>the</span>
  <span m='128590'>brain</span> <span m='128860'>works.</span> <span m='129770'>Jim</span>
  <span m='129940'>De Carlo</span> <span m='131230'>gave a</span> <span m='131470'>great</span>
  <span m='131710'>talk</span> <span m='132070'>about</span> <span m='134040'>how</span>
  <span m='134200'>the</span> <span m='134290'>features</span> <span m='134710'>we</span>
  <span m='134860'>see</span> <span m='135200'>in</span> <span m='135310'>deep</span>
  <span m='135550'>networks</span> <span m='136060'>are</span> <span m='136420'>similar</span>
  <span m='136720'>to</span> <span m='136820'>the</span> <span m='136860'>features</span>
  <span m='137170'>of</span> <span m='137230'>the</span> <span m='137320'>brain.</span>
  <span m='137860'>And</span> <span m='137900'>we</span> <span m='138040'>know</span>
  <span m='138250'>that</span> <span m='139060'>the</span> <span m='139150'>brain</span>
  <span m='139390'>is</span> <span m='139450'>constantly</span> <span m='139930'>undergoing</span>
  <span m='140320'>these</span> <span m='140440'>kind</span> <span m='140620'>of</span>
  <span m='140710'>changes.</span> <span m='141130'>So</span> <span m='142750'>we're</span>
  <span m='143170'>curious</span> <span m='143560'>scientifically</span> <span m='144190'>to</span>
  <span m='144310'>see</span> <span m='144550'>how</span> <span m='144910'>these</span>
  <span m='145150'>computer</span> <span m='145510'>models</span> <span m='146140'>respond</span>
  <span m='147610'>in</span> <span m='148360'>understanding</span> <span m='148960'>how</span>
  <span m='149080'>these</span> <span m='149230'>two</span> <span m='149380'>systems</span>
  <span m='149930'>are</span> <span m='150010'>the</span> <span m='150100'>same</span>
  <span m='150460'>or</span> <span m='150550'>different.</span> <span m='151570'>But</span>
  <span m='151750'>also</span> <span m='151960'>from</span> <span m='152140'>an</span>
  <span m='152210'>engineering</span> <span m='152630'>context</span> <span m='154660'>online</span>
  <span m='155050'>learning</span> <span m='155440'>where</span> <span m='156040'>the</span>
  <span m='156160'>network</span> <span m='156550'>is</span> <span m='157060'>changing</span>
  <span m='158500'>while</span> <span m='158860'>it's</span> <span m='159040'>learning</span>
  <span m='160240'>is</span> <span m='160720'>going</span> <span m='160990'>to</span>
  <span m='161110'>be,</span> <span m='161810'>I</span> <span m='161910'>think,</span>
  <span m='162110'>a</span> <span m='162210'>much</span> <span m='162280'>larger</span>
  <span m='162700'>part</span> <span m='163150'>of</span> <span m='163540'>the</span>
  <span m='163690'>use</span> <span m='164020'>of</span> <span m='164170'>machine</span>
  <span m='164500'>learning</span> <span m='164770'>going</span> <span m='165010'>forward.</span>
  </p><p><span m='166040'>So</span> <span m='166180'>understanding</span> <span m='167290'>how</span>
  <span m='167560'>stable</span> <span m='168040'>these</span> <span m='168250'>things</span>
  <span m='168520'>are</span> <span m='169720'>to</span> <span m='170290'>constantly</span>
  <span m='170830'>changing</span> <span m='171940'>parameters,</span> <span m='172870'>I</span>
  <span m='172930'>think,</span> <span m='173170'>will</span> <span m='173290'>be</span>
  <span m='173650'>quite</span> <span m='173890'>informative</span> <span m='174460'>for</span>
  <span m='174610'>those</span> <span m='174970'>kind</span> <span m='175120'>of</span>
  <span m='175180'>studies.</span> <span m='175870'>Being</span> <span m='176080'>able</span>
  <span m='176260'>to</span> <span m='176350'>explore</span> <span m='178600'>new</span>
  <span m='179350'>types</span> <span m='179650'>of</span> <span m='179710'>materials</span>
  <span m='180430'>and</span> <span m='181480'>learn</span> <span m='181690'>a</span>
  <span m='181750'>lot</span> <span m='181990'>about</span> <span m='182680'>both</span>
  <span m='182860'>computer</span> <span m='183190'>vision</span> <span m='183490'>and</span>
  <span m='183580'>neuroscience has</span> <span m='184960'>been</span> <span m='185170'>a</span>
  <span m='185200'>lot</span> <span m='185380'>of</span> <span m='185440'>fun.</span>
  <span m='186180'>And,</span> <span m='186280'>certainly,</span> <span m='186640'>informative</span>
  <span m='187680'>deep</span> <span m='187960'>learning</span> <span m='188900'>is</span>
  <span m='189180'>a</span> <span m='189250'>very</span> <span m='189610'>hot</span>
  <span m='189820'>topic</span> <span m='190240'>right</span> <span m='190420'>now.</span>
  <span m='190820'>So</span> <span m='190990'>being</span> <span m='191230'>able</span>
  <span m='191500'>to</span> <span m='191950'>dive</span> <span m='192250'>hands</span>
  <span m='192580'>in</span> <span m='192730'>a</span> <span m='192790'>little</span>
  <span m='193010'>bit</span> <span m='193860'>and</span> <span m='193990'>get</span>
  <span m='194110'>some</span> <span m='194290'>experience</span> <span m='194830'>working</span>
  <span m='195190'>with</span> <span m='195340'>these</span> <span m='195790'>models</span>
  <span m='196180'>and</span> <span m='196270'>some</span> <span m='196390'>of</span>
  <span m='197290'>the</span> <span m='197410'>latest</span> <span m='198550'>software</span>
  <span m='199000'>packages,</span> <span m='199570'>I</span> <span m='199660'>think,</span>
  <span m='199810'>will</span> <span m='199930'>be</span> <span m='200110'>useful</span>
  <span m='200440'>going</span> <span m='200680'>forwards</span> <span m='201060'>too.</span>
  </p>
type: course
uid: 48effe198a4cdae5a0f4f070d0d2025f

---
None