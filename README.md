
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

CMPD333
TOPIC O2: CYBER ATTACKS
OUTLINE
• Part 1: Types of Cyber Attacks
• Part 2: Malicious Software
Overview
3
• Let’s have a read:
• Hackers Are Going 'Deep-Sea
Phishing,' So What Can You Do
About It? | Threatpost
• Phishing Attacks Skyrocket with
Microsoft and Facebook as Most
Abused Brands | Threatpost
Common Threats to End Users
• Threats and vulnerabilities are the main
concern of cyber security when
protecting Asset.
• Two situations are especially critical:
1. When a threat actor acts to harm the
asset, a risk will occur. (Thief -> Steal)
2. When a Vulnerability causes the Asset
to be open to risk. (Hole on the fence)
• ATTACK causes the risk to happen
4
Term Example in Nora’s
scenario
Example in cyber
security
Asset Scooter Employee database
Threat Steal scooter Steal data
Threat actor Thief Attacker, hurricane
Vulnerability Hole in fence Software defect
Attack vector Climb through hole in
fence
Access web server
passwords through flaw in
OS
Likelihood Probability of scooter
stolen
Likelihood of virus
infection
Risk Stolen scooter Virus infection or stolen
data
PART 1: Cyber Attacks
Identifying Types of Cyber Attacks
• Client-side Attacks
• Web Attacks
• Network Attacks
• Wireless Attacks
• Social Engineering Attacks
6
Client
-side / Host Attacks
• Most common attacks are those
made on desktop PCs, often
known as clients or host. • For most companies, it means
systems that use the Windows
operating systems, as well as
those that use Mac OS and Linux.
• Most of those clients are always
connected to the organization’s
network.
• Newer attacks also focuses on
tablets and smart phones too!
7
Privilege escalation
• It begins by stealing one user’s account
then proceed to attempt to gain
elevated access to other resources.
• E.g.: Transitive attack - take advantage
of existing privileges to gain additional
attacks.
• Attackers take advantage of permissions
on one system (A) that allow access to
another system (B), which is trusted by a
third system (C).
• Then, despite not having rights to take
action on C from system A, an attacker
can use a transitive attack to pass
through otherwise strong security.
8
Insider Threats • Members of your own organization’s staff,
or others who already have privileges to
access or administrate your network and
systems, can use privilege escalation as
well.
• Even users who have been granted only
low
-level access can use privilege
escalation attacks, install malware, or
provide their credentials or data to third
parties.
• Considering insider’s threat does not
always mean the employee has ill
intentions, sometimes they were just
manipulated to do so.
9
Zero-Day attacks
• Our devices usually have
vulnerability or certain
feature to patch.
• Attacks that occur before
the vulnerability is
announced or fixed, is
known as zero-day
attack.
10
• There will be no patch available for a zero-day exploit when it occurs.
• Because a zero day attack doesn’t have a patch available, this can quickly
compromise hundreds or thousands of systems. Fortunately, when these attacks do
occur, the worldwide information security community reacts quickly.
• One example of zero day library can be accessed from: Zero-day Vulnerability Database - zeroday.cz

Zero-day exploits are when a malware exploits the vulnerability in software it is sometimes called zero hour or day zero attack in this video you will learn what zero day exploits is and how to stay away but before we start press the like button and subscribe to our Channel what is zero day exploits software is released for the users after several testing phases however it is never perfect there are always unforeseen 

 Flaws to resolve these issues the developer subsequently releases updates the problem could be reported by the user or discovered by self testing however when this vulnerability is discovered by criminally inclined people it can be exploited for nefarious purposes they can use it to gain illegal access to users computers by injecting a malware this type of vulnerability is called zero day vulnerability when an attacker exploits it 

 It's called zero day exploits attackers exploit these vulnerabilities by various means web browsers and software like Java and flash are more vulnerable so attackers might locate unsecured users through email attachments or software bundles zero-day attacks occur within a specific time frame known as a vulnerability window this is the time beginning from the first vulnerability exploit to the point at which a threat is countered zero day attacks are 

 Strategically implemented to cause maximum damage within a short span of time how to stay away from zero day exploits as you know there are no immediate fixes available to resolve the exploit because the developer is still unaware of its existence for a better protection you should have a behavioral blocker installed on your system it monitors the behavior of all programs when a program takes action that matches the malware 

 It blocks that program thus the zero-day attack is prevented malware Fox anti-malware has a behavioral blocker integrated into its system and is a proven anti-malware product that safeguards users against zero-day attacks so download and install malware Fox when the loophole is discovered the developers release security patches so you should install the security patches immediately whenever they are available by following these simple steps you 

 Could prevent zero-day exploit if the information in this video helps you don't forget to press the like button and subscribe to our channel we keep uploading such informative videos so press the bell button to receive the alert when we do that 

Identifying Types of Cyber Attacks
• Client-side Attacks
• Web Attacks
• Network Attacks
• Wireless Attacks
• Social Engineering Attacks
11
Web Attacks
• Web application are usually run from a browser.
• The attacker attempts to breach a web application.
• Common attacks of this type are:
• Cross Site Scripting (XSS)
• SQL injection
12
Cross-site scripting (XSS)
• Exploitation of a web application
vulnerability that allows
attackers to inject scripts into the
webpages that are served to
visitors of a website. XSS relies
on the user’s trust of the site.
• E.g.: The Samy worm, the
largest known XSS worm,
infected over 1 million MySpace
profiles in less than 20 hours.
13

I'm gonna show you the most popular way to hack a website where you can steal private information, hijack accounts, take over web pages and other illegal things to get you thrown in jail HOLD ON! This isn't for illegal activity,
it's for educational purposes only. Notice, the lights are on, I'm not wearing a hoodie and I don't even have a Matrix-themed terminal. So there's NO crime goin' on here. You have to promise me you'll use this information for GOOD and not EVIL. 

 So when you're ready, this is the recipe for the basics of Cross-Site Scripting. Hello, world! I'm Jesse from Chef Secure. Cross-Site Scripting, or XSS,
is a security vulnerability in web applications That allows evil hackers to inject their
own code inside a web page. Yep. That's bad. With the power of scripting,
cybercriminals can use your web applications to steal passwords, install malware or WORSE... The first step in Cross-Site Scripting
is to inject a script element into a web page Now, web pages are built using HTML,
which uses tags to create elements. Yep. There are a lot of 'em. Let's get started.
Go to the  Script Injection  example for this recipe below, 

 And pause the video when you need to,
so you can follow along and gain hands-on experience rather than just sitting there all awkwardly,
watching me do everything by myself. You can see that when you type something in and click the UPDATE button, it gets rendered on the page. So if you add more HTML,
what do you think would happen? Open an HTML tag using
less-than and greater-than characters surrounding an element name,
like p for paragraph Then add some content, and then add a closing tag after that – which is just the same as an opening tag
only there's a slash in front of the element name. Then click the  UPDATE  button. 

 You see that instead of writing text,
you actually changed the HTML of the web page by adding a new paragraph element. While simple, this is very, very powerful,
because JavaScript controls the web page. And if you can inject a  script  element instead, you now control exactly what happens in the browser. And THIS is how XSS works. So go ahead and inject  script  tags this time. Start with your opening script tag,
followed by your closing script tag. Now for the content that goes inside... This, my friends, is where we enter
the f-[bleep]-d up world of JavaScript. ( phone buzzing ) ( phone buzzing ) 

 WONDERFUL world of JavaScript! Javascript can be...
confusing at times. But what it does well, it does EXCEPTIONALLY well like letting you hack websites or... making them more INTERACTIVE. Performing actions in JavaScript is like any other programming language
where you just call functions. You can do this by typing the name followed by  parenthesis . And anything that goes inside the parenthesis gets passed as data, or arguments,
that the function can use. AND like other programming languages,
you can set values using an  equals sign . Right now, try calling the
alert function within your script tags. 

 So type in alert followed by parenthesis then click the UPDATE button
and watch your script execute. Because you see this alert pop up it means your script was
injected into the page successfully and ran due to an XSS vulnerability. While you're at it, get some practice
with arguments as well. So type in the number 1 to the alert function. Click the UPDATE button
and you'll see it alert 1. Or pass in text surrounded by
either single or double quotes to make a  string ,
and you can alert something you really love. I'm going to alert food. Because I love food. 

 I'm always thinking about – WAIT A SECOND! CHEF? Secure... Alerting is the most common function used by
both cybercriminals and security researchers alike to find vulnerabilities in websites. Now keep in mind that the alert function
is just a placeholder showing that a script can be injected. And once a vulnerability is found an attacker can easily replace this with a
malicious exploit that causes much more damage. Consider something simple: instead of alerting in our example,
let's just destroy the whole web page by removing all the HTML. 

 In JavaScript, document.documentElement.innerHTML
contains all the HTML of the web page, so just change it by setting it equal to an empty string. In our example, if we type that in: Click the UPDATE button and... it's gone. I'm gonna show you more about how
cybercriminals can exploit websites in a later recipe, but if you're just testing for vulnerabilities,
an alert is really all you need most of the time. So from here, what you really need is just
to be creative and explore so you can find more vulnerabilities. Say you need to type in something in a website,
such as a username or a status update, there's always a chance that it could
contain an XSS vulnerability, so it's worth a shot. Of course websites do have protections against XSS, 

 Some of them even built directly into
the frameworks on which they're built. But despite this, and despite
the frameworks being around for several years, the number of XSS vulnerabilities is still rising like crazy! And that's because writing secure,
resilient code can be quite tricky at times. And even with automatic protection,
you can still screw things up pretty badly. Trust me.
I've done it more than once. And I'll do it again,
I promise! But that's the point of having defense in depth,
which I will teach you as we go along in this course. But mistakes happen,
so let's look on the bright side: at least there are plenty of vulnerabilities to find and fix before cybercriminals can come
and hack your application. 

 Wait, that's not comforting at all... But that's all the time I have for now.
Good bye, friends. 

SQL Injection • Most common attacks against
web applications.
• Rely on injecting Structured
Query Language (SQL)
instructions into an application’s
input in a way that causes the
application to use its privileges
to run the commands against the
database it uses.
14

Sequel injection is one of the top three most common web app risks and it's probably in part because of how simple it is to perform so who's most vulnerable any website that sequel database driven with poor code so how does it work well this attack is very commonly done on login screens so let's first see what's happening your username and password after they're submitted your poorly designed site the name and 

 Password strings are directly inserted into a sequel statement which probably looks like this with this statement the application is asking the server do we have a user with the name Chris and the password my past one and if so it grants the user access to their account so the first thing an attacker will do is find out if the site is using a sequel database by entering a single quote into the username field I'm submitting single quotes are special characters in the 

 Sequel language and using them as part of a username will cause an error if the website doesn't check for them once the error message is displayed the attacker can confirm that the websites using sequel as well as other useful information and now the real injection begins the attacker can enter the following command logic which will render the following command the command will force the selection of a valid user name because the evaluation of one 

 Equals one is always true now most of the time the server will login the attacker with the credentials of the first user in the table the range of command manipulations is vast the record retrieval to complete table dilution so you can and how damaging this exploit can be to a website so how can we prevent this form of attack well make sure that you do the necessary string checking for special sequel characters it's really 

 Not that many more lines of code and it's most definitely worth the time there's also automated software available that can check your entire web application for injection as well as other vulnerabilities so you should check it out it's called rational AppScan it's really awesome software that's it for now I hope you learned something 

Identifying Types of Cyber Attacks
• Client-side Attacks
• Web Attacks
• Network Attacks
• Wireless Attacks
• Social Engineering Attacks
15
Type Characteristics
Spoofing
Provides false information on a network

How to prevent spoofing attacks cyberattacks come in many forms such as crippling infection DDoS attack password attack sequel injection and so on there are certain attacks that are underhanded spoofing is one such cyber attack that can breach enterprise networks without even being detected the spoof attackers have ample amount of time launch the attack against the network of spoofing attacks our email spoofing 

 This form of spoofing is done by imitating the domain our email address with slight deviations from the original the email may contain links to malicious web sites or malware caller ID spoofing this form of spoofing is done by disguising the phone numbers when making calls to the receivers and extract sensitive information such as ATM PIN password or social security number IP spoofing this involves The Masquerade 

 Of a computer IP address to keep the identity of the malicious attacker hidden the attackers use the IP address to penetrate into the networks to prevent common spoof attacks there are a range of steps you can implement to keep yourself protected from spoofing attacks some of the best ways are deploy spoof protection tool use encrypted protocols packet filters and VPNs install firewalls 

 Use antivirus software two factor authentication go here to know more about spoofing and ways to prevent it is one of the leading cybersecurity service providers in the USA we provide cutting-edge security solutions to ensure that the sensitive data is safe want to know more about our services contact us 

Packet Sniffing Access to credentials, files, and any other information
Man-in-the-middle
Read, modify, and in some cases they can even change the
packets

- Picture it, you don't have mobile data, so you need to connect to a public Wi-Fi. Then you have to buy something
from a random online store. And in a few days, your bank
account balance goes to zero. All right guys, so today I'm
going to tell you everything about man-in-the-middle attacks
and how to prevent them. But first, before you fall victim to any unsolicited attacks, or if you wanna enjoy
promotions and discounts, make sure you subscribe to our channels for the latest and all the best VPNs. 

 You might use public Wi-Fi
networks often, and why not? It's totally free and a convenient way to not spend your mobile data. But have you ever thought
about your internet and device security when doing so? Many of these public
networks are susceptible to man-in-the-middle attacks
where your data can be read, stolen and altered by cyber criminals. Man-in-the-middle attacks are some of the most common cyber attacks. Why, because it's easy and
potentially very lucrative. Not only can you expose your
financial details this way, 

 But you also risk losing
all your personal, valuable information because of it. So what are man-in-the-middle attacks? As the name suggests,
the bad guy inserts him or herself on a communication
between two devices and reads the traffic
without anyone noticing. Usually those two devices are your laptop and the Wi-Fi router. If you're not using an
encrypted connection, which usually happens when
you visit an insecure website, the man in the middle can learn all sorts of
sensitive information. 

 So in short, a man-in-the-middle
attack can lead to data and identity theft, online
bank information exposure and any other information
you don't want others to see going to someone malicious. Even HTTPS servers are very vulnerable to man-in-the-middle attacks. As recently as 2016, it was found that 95% of
HTTPS servers are vulnerable. Scary, right? It's not just about laptops either. I mean, think about it. What device do you use the most 

 And need the most protection on? That's right, your phone. You carry it with you
to the shop, to the cafe and you even connect to
strange public Wi-Fi connection so you don't have to use your mobile data. Believe it or not, phones are just as susceptible to man-in-the-middle
attacks as any other device. Fortunately, there are ways to preventing man-in-the-middle attacks and VPN providers are the best way to go. These services encrypt your connection, 

 Which will protect you from
man-in-the-middle attacks, even if you're visiting
insecure HTTP websites. Be sure to click the popup banner, to see our full list of the
best VPNs and get up to 84% off. If you're not sure
which VPNs are the best, I can tell you now that you
should either go for NordVPN, ExpressVPN or Surfshark. The reason be is that all three offer
top notch security features that especially prevent
man-in-the-middle attacks. Some security features,
including location masking, bypassing geo-blocking
and internet censorship 

 And overall internet security posture. All of these features
are especially important if you plan on regularly using
open or public connections. You can also try to prevent them yourself by making sure you don't open dodgy emails asking you to update your credentials, installing antivirus software and ensuring all the sites
you visit start with HTTPS, because the S means it's a secure page. Some common types of middlemen attacks include creating fake
interactions, websites and unsecure URLs without you noticing. 

 Unsecure server connections,
email hijacking, fake Wi-Fi connections
and stealing passwords, addresses and other sensitive information you provide the certain web pages. While internet thieves or
man-in-the-middle attacks are sly and difficult to notice, you can never hurt to learn
more about avoiding them. Getting solid VPN software and keeping your data to yourself. No one wants to wake
up with a major deposit out of their account due to
stolen banking details, right? And that's it guys. 

 Be sure to check out
some awesome VPN deals in the description below and subscribe to our channel
for more awesome videos. Thanks for watching. 

Replay Attacks
Uses previously captured data to replay a connection,
authentication, or other session

Hi this is Bob he would like to log in his web mail account let's see what happens Bob starts a login session with the server this is Eve she would like to know Bob's password so that she will be able to send emails pretending to be Bob Eve listens to Bob's login session Bob types his username and password in the login page and sends this information to server Eve by listening to the 

 Transportation between Bob and the server obtains Bob's credentials if the username and password are correct Bob gets a permission to log in Eve will now be able to log into Bob's account by using Bob's username and password this is a well-known attack named man in the middle we suggest a different authentication method that solves this problem when Bob tries to log into his email account the email server will send him a challenge a series of six random 

 Decimal digits as Eve is listening to Bob's session with the server she will also obtain the challeng the challenge the shared secret between Bob and the server is a very simple formula to manipulate this challenge let's assume Bob has chosen that the secret formula is multiplying the first number in the challenge named a with the second number in the challenge named B and then subtracting one in this case for this challenge the response equals to seven 

 Bob sends the response back to the server the server receives Bob's answer and lets him in as Bob was able to prove his identity without disclosing his password eve even if has listened to the whole login session will not be able to deduce the formula if she tries to log in she will get a new challenge she will not be able to calculate the response and thus will not be able to steal Bob's identity now after you are familiar with the new authentication 

 Method you are asked to register by choosing a username type your email address and the most important part to choose a secret formula this will be the secret you will share with the server then using the secret formula you have chosen you will have three Tri trials to log into the system the indicators in the upper left corner will show you if you succeeded to log in in each trial finally you'll be be asked to fill 

 A short survey thank you 

DoS and DDoS Crashing or disabling or damaging or destroying the
service/system
Denial of service (DoS) and distributed
denial of service attacks (DDoS)
17
DoS attack
typically uses one
computer and one
Internet
connection to
flood a targeted
system or
resource.
DDoS attack uses
multiple
computers and Internet
connections to flood
the targeted resource.
Identifying Types of Cyber Attacks
• Client-side Attacks
• Web Attacks
• Network Attacks
• Wireless Attacks
• Social Engineering Attacks
18
Wireless Attacks
• Most of us now use wireless technologies.
• Wireless attacks normally carried out to
target information that is being shared
through the networks wirelessly.
19
Type Characteristics
Rogue Access
Points
• Connects to your organization’s network that your
organization did not intend to place.
• Evil twins, rogue access points that pretend to be part of an
organization’s legitimate wireless network
War driving
Who drove around searching for wireless networks while in a
car

Hey FBI surveillance band play house parties clubhouse I got one Hendersons you about to get hacked oh hey gang what am i doing doing a little war driving what is war driving war driving is actually when somebody drives around a neighborhood driver out somewhere and actually trying to look for unsecured wireless networks all right so an easy way to prevent this an easy way to protect yourself from 

 This is actually hiding your SSID so what is your SSID your SSID is the name your network so when you go inside of Starbucks Starbucks Wi-Fi is the SSID SSID stands for service set identifier that doesn't really matter right now but the name of the network you can actually disable the neighborhood network and people won't actually see it when they're looking around another thing you can do especially for wardriving is reduce the range if I'm driving down the 

 Middle of the street I shouldn't be able to actually pick up your wireless network all right so make sure that the range is reduced to only inside your home maybe to your front porch and maybe a back porch any further than that is making you more susceptible to attacks another thing is just make sure that your network name right your network name just make it something normal because even with wardriving if you have sophisticated 

 Enough software even if you had the SSID they can still pick it up but if you reduce the range then they won't be able to pick it up in the middle of the street right and then if they are on Europe in the middle of your grass and mow your lawn and maybe hey maybe I should go talk to this guy so make sure that you reduce the range and to protect yourself from wardriving this is Duane from IT master key com this is a quick class about wardriving 

 Pop quiz waters warm driving bam because just what somebody drives wrong your neighborhood looking for unsecured wireless networks what's the easiest way to prevent that reduce the range your actual router you can do all of this through the admin portion of your router so hopefully enjoyed this and I'll see you in class 

Packet sniffing
and wireless
networks
Any data that isn’t encrypted can be captured and analysed
with ease
Identifying Types of Cyber Attacks
• Client-side Attacks
• Web Attacks
• Network Attacks
• Wireless Attacks
• Social Engineering Attacks
21
Social Engineering Attacks
• The process by which intruders gain access
to facilities, network, and even employees
by exploiting the generally trusting nature of
people.
• May come from someone posing as a
vendor, bank officer, police officer, etc.
• Using a variety of media, including phone
calls and social media, these attackers trick
people into offering them access to
sensitive information.
• Easy to accomplish in most organizations.
22
Type Characteristics
Phishing
Ask someone for a piece of information that you are missing by
making it look as if it is a legitimate request.
- Spear pishing
- Whaling
- Vishing

Phishing is a method of trying to gather personal
information using deceptive e-mails and websites. Stay tuned for what you need to know about
this increasingly sophisticated form of cyberattack. The goal of phishing is to trick an email
recipient into believing that the message is something they want or need — a request
from their bank, for instance, or a note from someone in their company — and to click
a link or download an attachment. "Phish" is pronounced just like it's spelled,
which is to say like the word "fish" — the analogy is of an angler throwing a baited
hook out there (the phishing email) and hoping you bite.
What really distinguishes phishing is that attackers masquerade as a trusted entity of
some kind, often a real — or plausibly real — person, or a company the victim might
do business with. It might be your boss, your bank or a company whose software you use.
Perhaps one of the most consequential phishing 

 Attacks in history happened in 2016, when
Russian hackers managed to get Hillary Clinton's campaign chair John Podesta to offer up the
password to his personal Gmail account. How did they do it? The hackers sent an email
warning Mr. Podesta that someone had his password and that he should change it immediately.
Clicking on a link in the email took him to a fake log-in page.
This is a classic ploy and one all of us hope we would see for what it is.
But email scammers are constantly honing their craft, trying new pitches and pulling new
strings. One way to get familiar with their tactics
is to study the email messages that scammers send.
Here are a few real-world examples and how they work:
1. Your account has been hacked The person sending this threatening phishing
message found a group email that was publicly available on the company website. Using that
list to target the message was smart. Not 

 So smart was the content of the message, in
which the would-be attacker reveals a lack of understanding of how malware works.
2. Password reset Taking advantage of the fact that no one wants
to miss a paycheck, messages like this one aim to trick the user into revealing important
data — often a username and password that the attacker can use to breach a system or
account. 3. Payment request
This email has enough information specific to the target company to give even the most
phishing-savvy recipients pause. The key to not getting caught in this trap is to know
your company's processes and be able to spot anomalies.
4. Charity donation Here the scammer is counting on the greed
and gullibility of the recipient. This theme of giving something away for free is a common
one and preys on human nature. The key thing to remember is if it sounds too good to be
true, it probably is. 

 Thanks for watching and stay safe out there! 

Tailgating or
“piggybacking”
A person impersonates a delivery driver and waits outside a
building

Cho tôi xem hai truyền phim sex Omen vs elfs wish that music comin from to me and nothing We get well niger special english with the food for the five Soul and she did you focus on the gardens of Turning and returning kem person And Again access to wishlist 

 Aborted or canceled live at Price Center for a person Who have all the voice Texas trong game king of the banker which ends Tonight I a person with love is near your pet Show and Tell Me That support and equity below to be treated with Online Super five senses of stay and the concert event was patient Again access your Network and Vietnamese for some advantages of aesthetic and Kibum etisalat in Golden Time and 

 Little Dragon people of and for you have Mercy of us on sweetness and forestry became FED up with reckoning temples palaces mô for the person per about their music And Dance With National Network and fun and Write success is certain foods for workstations and Find the way that ass for more information about Smoking and then it was seen What is the mortar or video district of business social and live if you might want to say this right đ A 

 Perfect Money is what are you doing my heart you're my office in this game you know is not elsewhere in tôi mãi đường vani justified Wow phân li fay Minion anh ạ 

Impersonation
Pretend to be someone you are not

[Music] you know getting dressed up in costumes and wearing masquerade outfits is kind of fun and it's interesting for you know Halloween maybe Mardi Gras but when it comes to a professional environment or your business people impersonating or doing hoaxes presenting themselves as someone that they're not actually isn't funny at all in a malicious cracker if they're going to do impersonation or 

 Masquerading which is really part of social engineering it's going to involve some preparation and some prior reconnaissance and information gathering before they attempt the exploit and impersonation is often a key factor masquerading is first attempted remotely through IP spoofing and then possibly over the phone maybe using email SMS texting instant messaging and then if none of those things get information that they need they'll do it in person 

 If the payoff from getting your data and your information is worth it the attacker can then obtain records about an organization your marketing plans your corporate secrets your formulas information about your employees your customers PII and other critical data if a cracker is gonna do social engineering and they're gonna pose as some other person what are some of the options they have well they can masquerade as a janitor or a cleaning service a pest 

 Control company they can be a fire inspector or a building inspector they may it poses a temporary or contract worker they may even position themselves as a security professional coming in doing a penetration test or an audit they may masquerade as a newly hired employee or a relative of somebody in management as a matter of fact use your imagination and think if you were a cracker what type of hoax or masquerade would you 

 Take on to trick somebody into getting inside to get access to a system employees should be well trained through security awareness programs to always be on the lookout for impersonators always politely ask for identification or authorization like a guest badge or a card if they notice somebody that seems like they just don't belong their policy may stay that employees don't confront suspects but instead escalate suspicious people to a supervisor a security guard 

 Or the security team a hoax is very similar and that the attacker tries to mislead people by presenting a false scenario hoaxes can come in person or through other means of communication like texting and email a hoax will often be attempted on holidays or other special days during major events like the US Super Bowl or the World Cup or the Olympics for example chain email messages are intended to trick mislead or scare recipients into forwarding the 

 Messages to many more recipients in this video we talked about the impersonation and hoaxing aspect of social engineering 

Vishing: (63) Watch this hacker break into a company - YouTube
Type Characteristics
Dumpster
Diving
Looking for treasure in someone else’s trash

Oh hey did you know that a hundred percent of dumpster crime takes place in a dumpster I didn't know that one either people will do this kind of stuff and then root around in your trash oh look tax form now I know your social don't do that kind of stuff make sure you're shredding your trash like this you want confetti cut to stuff that they can't assemble don't breathe that or you can burn your trash you may not have a 

 Burn bag like this but you can still burn your trash just take it out burn it don't throw stuff away like credit card forms either so offers that the credit card company sends you those are especially high on the list for identity thefts you never know what you can find in a dumpster there's a perfectly good Apple [Applause] 

Shoulder
Surfing
Watching someone “over their shoulder” when they enter
their sensitive data

Susan has been working with her current employer for a long time she has just recently promoted as a senior accountant in the finance department she has elevated access to a lot of sensitive financial information jon is the new employee and comes to susan's desk to discuss some technical details he watches over susan while she is 

 Entering her credentials susan doesn't know that john is an insider and trying to get elevated access to companies financial systems he now knows susan's password using susan's account john is able to authorize some fraudulent transactions susan realizes this but it is already too late the money has been transferred out shoulder surfing is a type of attack that criminals use to get elevated access to others accounts with watching 

 Over the shoulder while working on your computer be aware of people around you and protect yourself and your company 

PART 1b: Some
Examples
Malicious emails with password-protected
archives
• To make potential victims open the archives: fake
notifications about orders from large stores, various bills,
money transfers, resumes, or the promise of lots of money.
• The attached archives usually contained office documents
with macros or JavaScript scripts. When launched, the files
downloaded other malicious programs on the user’s
computer.
26
Malicious emails with password-protected archives
(cont.)
• The archive in the message contains
the Richard-CV.doc file with macros
that downloads representatives of the
spyware family.
• These malicious programs collect
confidential information about the user
and send it to the remote server.
27
Advance-fee scam
• Required to pay a fee
before receiving promised
stocks, services, money,
or products, which
ultimately are never given
28
How to Deal with
Social Engineering
Attacks?
29
How to Deal with Social Engineering
Attacks?
• DO NOT open emails in the spam folder or emails
whose recipients you do not know.
• DO NOT open attachments in emails of unknown
origin.
• Humans need to be trained – they are the weakest
link.
• Bi-annual training geared towards each user group (endusers, IT staff, managers, etc.) so that everyone is aware
of the latest attacks.
30
PART 2: Malicious
Software
Malware • What is malware (Malicious
Software)? • Software that enters a computer system
without the user’s knowledge or
consent and then performs an
unwanted and usually harmful action.
• Types of malware: • Viruses • Worms • Trojan horses • Spyware • Rootkits • Spam • Ransomware
32
Types of Malware
Malware Type Characteristics
Spyware Collects information about the user without the user’s
consent
Adware pushes you with endless ads and pop-up windows
Ransomware restricts access to your computer system and demands
that a ransom is paid
Rootkits Gain administrator-level control over a computer system
Anatomy of a Ransomware Attack: (24) Ransomware - Anatomy of an Attack – YouTube
Adware Spyware Ransomware

[Music] foreign imagine this you go online with your nice well-behaved browser only to see it fly into a virtual tantrum as an onslaught of advertisements either pops up slides in from the side or otherwise inserts itself to interrupt and even redirect your intended activity and no matter how much you click to 

 Close those windows they keep buzzing you like flies at a picnic that bothersome phenomenon is a result for madwear short for advertising supported software adware is unwanted software designed to throw advertisements up on your screen most often within a web browser typically it uses an underhanded method to either disguise itself as legitimate or piggyback on another program to trick 

 You into installing it on your pc tablet or mobile device adware generates revenue for its developer by automatically displaying online advertisements in the user interface of the software or on a screen that pops up in the user's face during the installation process and that's when you start seeing many types of ads pop up on your screen inviting you to click 

 Also you might experience new tabs opening a change in your home page findings from a search engine you never heard of mind you it does happen that legitimate software applications do use online advertising with ads that are typically bundled within the program and that display in ways the program developer specified adware is a different thing altogether you might download it without 

 Understanding its intent or it might land on your pc by means of legitimate software within which it's secretly buried whatever the path it all boils down to some program on your computer showing you advertisements that do not come from the websites you are visiting although some adware are not harmful it is still annoying to see those ads keep on popping spyware is unwanted software that 

 Infiltrates your computing device stealing your internet usage data and sensitive information spyware gathers your personal information and relays it to advertisers data firms or external users spyware is used for many purposes usually it aims to track and sell your internet usage data capture your credit card or bank account information or steal your personal identity 

 Spyware monitors your internet activity tracking your login and password information and spying on your sensitive information some types of spyware can install additional software and change the settings on your device so it's important to use secure passwords and keep your devices updated if you've ever been a victim of identity theft or credit card fraud you're not alone cyber crime statistics 

 Tell the story a total of 978 million people in 20 countries were affected by cyber crime in 2017. victims of cyber crime globally lost 172 billion dollars spyware contributed to those numbers spyware is one of the most common threats on the internet it can easily infect your device and it can be hard to identify spyware is a threat to businesses and 

 Individual users since it can steal sensitive information and harm your network ransom malware or ransomware is a type of malware that prevents users from accessing their system or personal files and demands ransom payment in order to regain access there are several different ways that ransomware can infect your computer one of the most common methods today is through malicious spam 

 Or mouse pam which is unsolicited email that is used to deliver malware the email might include booby-trapped attachments such as pdfs or word documents it might also contain links to malicious websites there are three main types of ransomware scareware scareware as it turns out is not that scary it includes rogue security software and tech support scams you might receive a pop-up message 

 Claiming that malware was discovered and the only way to get rid of it is to pay up if you do nothing you'll likely continue to be bombarded with pop-ups but your files are essentially safe a legitimate cybersecurity software program would not solicit customers in this way if you don't already have this company's software on your computer then they would not be monitoring you 

 For ransomware infection if you do have security software you wouldn't need to pay to have the infection removed you've already paid for the software to do that very job screen lockers when lock screen ransomware gets on your computer it means you're frozen out of your pc entirely upon starting up your computer a full-size window will appear often accompanied by an official looking fbi 

 Or u.s department of justice seal saying illegal activity has been detected on your computer and you must pay a fine however the fbi would not freeze you out of your computer or demand payment for illegal activity if they suspected you of piracy they would go through the appropriate legal channels encrypting ransomware this is the truly nasty stuff these are the guys who snatch up your 

 Files and encrypt them demanding payment in order to decrypt and redeliver the reason why this type of ransomware is so dangerous is because once cyber criminals get a hold of your files no security software or system restore can return them to you unless you pay the ransom they're gone and even if you do pay up there's no guarantee the cyber criminals will give you those files back 

rootkit

One type of malware is nastier than almost
any other. Let’s talk about rootkits. What is a rootkit? It’s a collection of malicious software
that’s hidden deep within the operating system of a computer. A rootkit might even hide at the level of
the kernel, which controls the entire system. It’s very hard to detect, and it may be
even harder to remove. A rootkit allows a hacker to have control
over your computer or software without you realizing it. A rootkit attack can compromise your system
in many different ways. A hacker can use it to: 

 Infect you with malware. Initiate a denial-of-service attack. Disable anti-malware software. Or even take over your device
A rootkit can end up on your system like any other malware. You can accidentally download it from an infected
website or a compromised USB drive. Or a hacker can use social engineering to
steal your access data and inject a rootkit into your computer. If you get infected, the removal can be complicated. Some rootkits can be detected and removed
by antivirus. In other cases, you may need to reinstall
your operating system. The best defense is prevention. 

 Don’t download software from unreliable
websites. Use only official websites or trusted online
stores. Don’t download shady attachments or click
on suspicious links.Do not use USB devices you don’t trust. Be wary of scammers and phishing messages. Never give personal info unless you’re sure
it’s safe. And keep your software updated. Stay safe! For all things online security, please subscribe
to our YouTube channel. 

Types of Malware
Code Type Characteristics
Virus
Attaches itself to program and propagates copies of itself
to other programs
Trojan horse Contains unexpected, additional functionality
Rabbit Replicates itself without limit to exhaust resources
Worm Propagates copies of itself through a network


Ways to Deliver Malicious Software
• Malware can be delivered in several
ways:
• Via software, messaging, and media
• Privilege escalation (exploiting the issues
of the computer's configuration to gain
elevated access to resources)
• Backdoors
• Logic bombs
• Botnets and zombies
39
Botnets and zombies • A zombie computer is similar to traditional Trojan
horse. • The difference between the two is that, instead of
only installing a keylogger and stealing your personal
data, zombies will work with other zombies, forming
what is called a “botnet” (or “zombie army”).
• The term “botnet” comes from combining the words
“robot” and “network”. For a much more fun
explanation, what this video: (24) What is a botnet? When IoT
devices attack
- YouTube
• Botnets are entire networks of computers controlled
and instructed to do a bunch of things, such as: • attack other computers, • send spam or phishing emails, • deliver ransomware, • spyware, or many other similar malicious acts.
40
Botnets and zombies
41
• Cybercriminals will lure you into a drive-by
download.
• Exploit vulnerabilities in websites and
software, such as your browser’s
outdated plugins.
• Trick you into clicking on links or opening
malicious email attachments.
• Once executed, the malicious code will
make contact with the Command & Control
server, the one that operates the botnet.
• Computer will remain idle, periodically
checking for instructions from the control
computer.
• Command & Control server will issue a
command and the botnet will launch an
attack.

[Music] malicious software or malware can harm your computer in a variety of ways and sometimes the effects are not known until it's too late what's worse your computer can become one of many infected with malware creating a botnet short for robot and network cyber criminals use special malware usually a Trojan horse to breach the security of several users computers 

 These take control of each computer and organize all of the infected machines into a network of bots which are unwitting tools that the cyber criminal can remotely manage the infected system may act completely normal with no warning signs a bot can be a PC Mac or even a smartphone oftentimes the cyber criminal will seek to infect and control thousands tens of thousands or even millions of computers so that they can act as the master of a large zombie 

 Network or bot network these botnets are capable of delivering many different types of cyber crimes such as DDoS attacks spreading malware online fraud and wide scale spam or phishing campaigns in some cases cyber criminals will establish a large network of sobbing machines and then sell access to the zombie network to other criminals either on a rental basis or as an outright sale spammers may rent or buy a network in order to operate a 

 Large-scale spam campaign the consequences of being part of a botnet can be very serious some risks include high internet bills slow and unstable computer performance potential legal implications if your computer is compromised and stolen personal data which can be used in blackmail or identity theft becoming a victim of a botnet attack is all too easy a common source of infection is downloading files from an unknown site or from 

 File-sharing even social media sites and apps can contain malware that can turn your computer into a bot high risk computers are ones with outdated internet security software or even none at all you can limit the risks by always verifying the site or app that you plan on downloading from and ensuring it is from a legitimate source however the best form of protection is installing effective anti-malware software against 

 Trojans and other threats always ensure that your computer is equipped with the latest internet security software in order to prevent becoming part of a botnet [Music] 

PART 3: Protection
Against Malware
Protecting Against Malware
Antivirus Program
• Cyber criminals develop and
deploy new threats on a daily
basis.
• The key to an effective
antivirus solution is to keep the
signatures updated. A
signature is like a fingerprint. It
identifies the characteristics of
a piece of malicious code.
Up-to-Date Software
• Today’s application-level
vulnerabilities pose the
greatest risk.
• While operating system
vendors are becoming more
and more responsive to
patching, most application
vendors are not.
User Awareness
• The weakest link in any system
is usually the user
• Inexperienced User can be
manipulated if the attackers
where their soft spots are
43
Protect Yourself Against Identity Theft
• Do not provide your personal information to anyone if it is not
necessary.
• Destroy documents that have personal information on them.
• Check your credit frequently.
44
Protect Yourself Against Cyber Stalking
• If you use public chat rooms, discussion
boards, and so forth, do not use your real
name.
• Set up a separate email account with an
anonymous service, such as Live, Gmail.
• Then use that account and a fake name online.
This makes it hard for an online stalker to trace
back to you personally.
• If you are the victim of online harassment,
keep all the e-mails in both digital and
printed format.
• Use some of the investigative techniques you
explore later in this book to try to identify the
perpetrator.
• If you are successful, then you can take the emails and the information on the perpetrator to
law enforcement officials.
45
Your task for Thursday
Watch some videos: Techniques used by
hackers
Anatomy of an IoT Attack: (24) Cisco - Anatomy of an IoT Attack
- YouTube
Anatomy of a Cyber Attack: (24) Anatomy of a Cyber Attack –
YouTube
47

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

# https://chat.openai.com/share/0beb0f51-84f3-4dcd-a1dc-fe32d8a72944

```
1. Which of the following is NOT a function available with iostream?
   A. cin
   B. cout
   C. endl
 = D. namespace


2. Which of the following describe about cin object?
   A. Store data from the keyboard only.
 = B. Accepts a stream of data from the standard input device.
   C. Outputs a stream of data from the standard input device.
   D. Accepts a stream of data from the standard output device.


3. A function prototype will tell the ____________ that there exist a function with this name defined at begin in the program and therefore it can be used even though the function has not yet been defined at that point.
   A. call
 = B. compiler
   C. computer
   D. prototype


4. In order to write and use our own function, we need NOT do these:

   I. Create a function prototype.
   II. Include header file for standard input output.
   III. Call the function whenever it need to be used.
   IV. Define the function at beginning of the program.

   A. I only
 = B. IV only
   C. I and III only
   D. I, II and III


5. Which of the following is a right example for the function call?
   A. add(int, int);
   B. add(num1, num2);
 = C. add(int num, int num2);
   D. void add(int num, int num2);


6. Which statement dynamically allocates an array of integers of n elements?
   A. int numbers[n];
   B. int *numbers[n];
   C. int numbers = new int[n];
 = D. int *numbers = new int[n];**


7. Which of the following is the proper keyword to deallocate memory in C++?
   A. free
   B. clear
 = C. delete
   D. remove


8. Choose the correct way(s) to declare a 2-dimensional array with 2 rows and 3 columns.

   I. int arr [2][3];
   II. int arr [3][2];
   III. int arr [ ][ ] = { 2, 3, 4 };
   IV. int arr [ ][ ] = { { 2, 3, 4 }, {5, 6, 7 } };

 = A. I only
   B. II only
   C. I and III only
   D. I, II and III


9. Which of the following is NOT describe about a structure?
   A. We can have pointers of type structures.
   B. Defining a structure is like defining a new data type.
   C. A structure may contain members of many data types.
 = D. A structure may contain function as members of its elements.


10. Which of the following is a properly defined struct?
    A. struct { int x; }
    B. struct my_struct int x;
  = C. struct my_struct{ int x; }
    D. struct my_struct{ int x; };


11. Which symbol is used to define the member of a class externally?
    A. :
    B. #
  = C. ::
    D. };


12. Which of the following is declare just like a regular member function, but with a name that matches the class name and without any return type?
    A. Cass
    B. Object
  = C. Constructor
    D. User-defined


13. The default constructor does not take any __________.
    A. return
    B. function
    C. data type
  = D. parameter


14. When constructor is invoked automatically?
    A. A class is defined.
    B. A class is referenced.
  = C. An object is instantiated.
    D. An object is called by a function.


15. What will be the output if the string syafiqah is entered in code Figure 1?

    Char name[20];
    cout << “Enter your name : ” ;
    cin.width(5);
    cin >> name;
    cout << name << endl;

    Figure 1

  = A. syaf
    B. syafi
    C. syafiq
    D. syafiqah


16. Which stream manipulator forces a floating point number to display a specific number of digits to the right of the decimal point?
  = A. fixed
    B. setw()
    C. width()
    D. scientific


17. Which stream manipulator is used to reset function showpos back to default display mode?
  = A. noshowpos
    B. stopshowpos
    C. cancelshowpos
    D. removeshowpoint


18. Which stream manipulator forces a floating point number to be output with its decimal point and trailing zeros?
    A. showcase
  = B. showpoint
    C. showarray
    D. noshowpoint


19. Which class file handle both file input and output?
    A. infile
    B. outfile
  = C. fstream
    D. ofstream


20. What does it mean by ofstream in C++?
    A. Delete the file.
  = B. Writes to a file.
    C. Reads from a file.
    D. Writes to a file & Reads from a file.


1. Which of the following correctly declares an array?
 = A. float rainfall[8];
   B. float rainfall;
   C. rainfall{8};
   D. rainfall[8] float;


2. Which reference modifier is used to define reference variable?
 = A. &
   B. $
   C. #
   D. >>


3. The standard output stream in C++ is represented by _______ operator.
 = A. <<
   B. >>
   C. ==
   D. %


4. The standard input stream in C++ is represented by _______ operator.
   A. <<
 = B. >>
   C. ==
   D. %


5. What will happen when we use void in argument passing?
 = A. It will not return value to its caller.
   B. It will return value to its caller.
   C. Maybe or may not be returning value to its caller.
   D. All of the above.


6. Which symbol is used to terminate a class definition?
   A. *
   B. &
 = C. };
   D. {


7. A function has been declared through the following prototype:

   float process salary (int, char);

   Which statement is true for this function?

 = A. This function returns no value.
   B. This function returns two values which are an integer and a character.
   C. During the function call, a value of type float is passed to the function.
   D. During the function call, two values are passed to the function.


8. What will be the output of the following code segment in Figure 1?

   enum Fruits {orange, apple, pear};
   Fruits Myfave = orange;
   cout << "My favorite fruit is: " <<Myfave;

   Figure 1

   A. My favorite fruit is orange
 = B. My favorite fruit is 0
   C. My favorite fruit is 1
   D. No output generator: error


9. Which the following is the correct function prototype for the function call below?

   functionABC (10, 2, 3.5) ;

   A. int functionABC(float, float, int);
   B. void functionABC(int, float, int);
 = C. void functionABC(int, int, float);
   D. void functionABC(int, float);


10. What is the output of the following code segment in Figure 2?

    #include<iostream>
    using namespace std;
    int main() {
       int a[] = {10,20,30};
       cout<<*a+1;
    }
 
    Figure 2
 
    A. 10
    B. 20
  = C. 21
    D. 11


11. If x is an integer and p and q are pointers to integers, which of the following assignments will not cause a compilation error?
    A. p = **&q;
    B. x = *&p;
  = C. q = *&x;
    D. p = &x;


12. Which the following is used to call function within a class?
    A. Member
    B. Operator
    C. Class
  = D. Method


13. What will be the output of the following code segment in Figure 3?

    void fun (int*, int*);
    int main(){
       int i=5, j=2;
        fun (&i, &j);
         cout << i << j;
        return 0;
    }
    void fun (int *i, int *j)
    {
        *i = *i**i;
        *j = *j**j;
    }
 
    Figure 3

    A. 5 2
  = B. 10 4
    C. 2 5
    D. 25 4


14. All of the following is a valid access specifier in a class EXCEPT:
    A. private
    B. public
    C. protected
  = D. encapsulated


15. How many times a derived class can inherit from a base class?
  = A. One
    B. Maximum three
    C. Maximum five
    D. More than one
```

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>




















1. OS are developed to fulfill the following set of objectives: - 

   ```
     A. free, open source, evolvability
     B. convenience, evolvability, closed source
     C. efficiency, cheap, reliable
   = D. Convenience, efficiency, ability to evolve 
   ```

<br>

2. The following components makes a whole computer environment **EXCEPT** 

   ```
     A. user
   = B. malware
     C. software
     D. hardware 
   ```

<br>

3. "Internal and external software and hardware errors“
    Which of the following aspect is fulfilled by the above statements?? 

   ```
   = A. Error detection and response
     B. Program development
     C. System Access
     D. Accounting 
   ```

<br>

4. Select the correct order of OS evolution. 

   ```
     A. Serial Processing > Multiprogramming batch system > Time sharing system > Simple batch System.
   = B. Serial Processing > Simple batch System > Multiprogramming batch system > Time sharing system.
     C. Time sharing system > Serial Processing > Multiprogramming batch system > Simple batch System.
     D. Multiprogramming batch system >Serial Processing > Time sharing system > Simple batch System. 
   ```

<br>

5. Generally, for any scheduling policies, selection functions must be based on the following criteria, **EXCEPT** 

   ```
     A. execution characteristics of process.
     B. resource requirement.
   = C. process size.
     D. priority. 
   ```

<br>

6. An operating system could employ virtual memory with the following specifications **EXCEPT** 

   ```
     A. hardware support paging
   = B. algorithm for disk scheduling
     C. hardware support segmentation
     D. algorithm for various memory management 
   ```

<br>

7. Frame could be defined as 

   ```
     A. variable-length block of secondary memory
     B. fixed-length block of secondary memory
     C. variable-length block of main memory
   = D. fixed-length block of main memory 
   ```

<br>

8. Select the relevant tables that are maintained by the operating system.
   ```
   I – Memory Table
   II – I/O Table
   III – Deadlock table
   IV – State table
   ```

   ```
     A. All of the above
     B. I, II and III only.
   = C. I and II only
     D. III and IV only 
   ```

<br>

9. Primary memory is also known as 

   ```
     A. secondary memory
     B. hard disk memory
     C. virtual memory
   = D. real memory 
   ```

<br>

10. “If a frame is locked, it may not be replaced by any incoming frames.”
    The statement above refers to the occurrence of 

    ```
    = A. frame locking
      B. starvation.
      C. deadlock
      D. livelock 
    ```

<br>

11. Which of the following is an example of non-parasitic malware? 

    ```
      A. Virus
    = B. Worms
      C. Backdoor
      D. Logic bomb 
    ```

<br>

12. The following types of scheduling are related to the 7-states Process Model **EXCEPT**  

    ```
    = A. I/O scheduling
      B. long-term scheduling
      C. short-term scheduling
      D. medium-term scheduling 
    ```

<br>

13. “Doing inefficient tasks by swapping pieces to and from main memory to secondary memory rather than executing instructions”.
    The statement above refers to 

    ```
      A. livelock
    = B. thrashing
      C. deadlock
      D. dispatcher 
    ```

<br>

14. Categorize the following machine-readable hardware correctly.
    ```
    I – External Hard Disk
    II – Sensors
    III – Keyboard
    IV – Joystick
    V – Modem 
    ```

    ```
    = A. I and II only
      B. III, IV and V only
      C. I, II and IV only
      D. III and V only 
    ```

<br>

15. In a generic File System Architecture, _________________ is considered as machine level equivalent. 

    ```
      A. basic file system
      B. indexed sequential
      C. logical Input / Output (I/O)
    = D. device drivers 
    ```

<br>

1. The following functions are all views in a computer system **EXCEPT** 

   ```
   = A. batch system.
     B. computer hardware
     C. application program
     D. utilities 
   ```

<br>

2. The following services fulfils convenience objective for operating system, **EXCEPT** 

   ```
     A. error detection and response
     B. program development
     C. accounting
   = D. I/O devices 
   ```

<br>

3. “The amount of time reserved for hardware setup for the purpose of running programs.” The given explanation best explains 

   ```
     A. installing time
   = B. setup time
     C. schedule time
     D. runtime 
   ```

<br>

4. A process could be defined as the following, **EXCEPT** 

   ```
     A. unit of activity characterized by execution of a sequence of instruction
   = B. entity that can be assigned to and executed on a memory.
     C. instance of program running on a computer
     D. program in execution. 
   ```

<br>

5. While a program is executing, it could be characterized by all the element as the following, **EXCEPT** 

   ```
   = A. thread
     B. identifier
     C. program counter
     D. accounting information 
   ```

<br>

6. Which of the following process state that is **NOT** relevant for 5-states process model? 

   ```
     A. Exit.
     B. Ready.
     C. Running.
   = D. Blocked/suspend. 
   ```

<br>

7. Select the relevant tables that are maintained by the operating system.
   ```
   I- Memory Table
   II- I/O Table
   III- Deadlock Table
   IV- State Table 
   ```

   ```
     A. I, II, III and IV.
     B. I, II and III.
   = C. I and II only.
     D. III and IV only. 
   ```

<br>

8. Atomic Operation could be defined as 

   ```
   = A. fixation or action that ensures sequence of operation to be indivisible
     B. section of code within process that request access to shared resources
     C. requirement of ensuring no two concurrent processes are in critical section at same time
     D. events occur simultaneously 
   ```

<br>

9. The following are all type of process interaction, **EXCEPT** 

   ```
     A. unaware of each other
   = B. indirectly unaware of each other
     C. directly aware of each other
     D. indirectly aware of each other 
   ```

<br>

10. Primary memory is also known as 

    ```
      A. secondary memory
      B. virtual memory
    = C. real memory
      D. hard disk memory 
    ```

<br>

11. Whenever a new process is created, a series of actions are done by OS. The following are the processes, **EXCEPT** 

    ```
      A. create or expand other data structures
      B. assigns a unique process identifier
    = C. assigning a new process state
      D. set up appropriate linkages 
    ```

<br>

12. Among all of Disk Scheduling Algorithms, _________________ chooses tracks with the minimum seek time, starting from the disk arm’s position. 

    ```
      A. SCAN
      B. C-SCAN
    = C. SSTF
      D. FIFO 
    ```

<br>

13. Which of the following that is **NOT** the common type of buffering in traditional OS? 

    ```
      A. Circular Buffer
      B. Double Buffer
    = C. Internal Buffer
      D. Single Buffer 
    ```

<br>

14. “If a frame is locked, it may not be replaced by any incoming frames.”
    The statement above refers to the occurrence of 

    ```
    = A. frame locking
      B. starvation
      C. livelock
      D. deadlock 
    ```

<br>

15. The following set of operations are commonly doable in any OS, **EXCEPT** 

    ```
      A. create
    = B. code
      C. delete
      D. write CO2 
    ```

<br>

1. In internal fragmentation, memory is internal to a partition and _________________. 

   ```
     a) is being used
   = b) is not being used
     c) is always used
     d) none of the mentioned
   ```

<br>
 
2. A solution to the problem of external fragmentation is _________________. 

   ```
   = a) compaction
     b) larger memory space
     c) smaller memory space
     d) none of the mentioned
   ```

<br>
 
3. Another solution to the problem of external fragmentation problem is to _________________. 

   ```
   = a) permit the logical address space of a process to be non-contiguous
     b) permit smaller processes to be allocated memory at last
     c) permit larger processes to be allocated memory at last
     d) all of the mentioned
   ```

<br>
 
4. _________________ is generally faster than _________________ and _________________. 

   ```
   = a) first fit, best fit, worst fit
     b) best fit, first fit, worst fit
     c) worst fit, best fit, first fit
     d) none of the mentioned
   ```

<br>

5. Consider the following page reference string.<br><br>
12342156212376321236<br><br>
For FIFO page replacement algorithms with 3 frames, the number of page faults is? 

   ```
   = a) 16
     b) 15
     c) 14
     d) 11

     ANSWER : 16
   ```

<br>

6. When will external fragmentation not occur? 

   ```
     a) first fit is used
     b) best fit is used
     c) worst fit is used
   = d) no matter which algorithm is used, it will always occur (answer)
   ```

<br>
 
7. _________________ occurs when the memory allocated to a process is slightly larger than the process. 

   ```
   = a) internal fragmentation
     b) external fragmentation
     c) both internal and external fragmentation
     d) neither internal nor external fragmentation
   ```

<br>
 
8. A process is thrashing if _________________. 

   ```
     a) it spends a lot of time executing, rather than paging
   = b) it spends a lot of time paging than executing
     c) it has no memory allocated to it
     d) none of the mentioned
   ```

<br>
 
9. When a process is copied into the main memory from the secondary memory according to the requirement. This concept refers to _________________. 

   ```
     a) Paging
   = b) Demand paging
     c) Segmentation
     d) Swapping
   ```

<br>
 
10. _________________ happens when a program tries to access a page that is mapped in address space but not loaded in physical memory. 

    ```
      a) segmentation fault occurs
      b) fatal error occurs
    = c) page fault occurs
      d) no error occurs
    ```

<br>
 
11. Why are page replacement algorithms required? 

    ```
      a) to replace pages faster
      b) to increase the page fault rate
    = c) to decrease the page fault rate
      d) to allocate multiple pages to processes
    ```

<br>
 
12. One of the replacement replacement algorithm which is the optimal replacement algorithm is considerably difficult to implement. This is because _________________. 

    ```
      a) the algorithm requires a lot of information
    = b) the algorithm requires future knowledge on the page reference
      c) the algorithm is too complex
      d) the algorithm is extremely expensive
    ```

<br>
 
13. When the memory allocated to a process is slightly larger than the process, then _________________. 

    ```
    = a) internal fragmentation occurs
      b) external fragmentation occurs
      c) both internal and external fragmentation occurs
      d) neither internal nor external fragmentation occurs
    ```

<br>
 
14. The techniques which move the program blocks to or from the physical memory is called as _________________. 

    ```
      a) Paging
    = b) Virtual memory organisation
      c) Overlays
      d) Framing
    ```

<br>
 
15. The main aim of virtual memory organisation is _________________. 

    ```
      a) To provide effective memory access
      b) To provide better memory transfer
      c) To improve the execution of the program
    = d) All of the mentioned
    ```

<br>
 
16. What is true about memory management? 

    ```
      A. Memory management keeps track of each and every memory location
      B. It decides which process will get memory at what time.
      C. It tracks whenever some memory gets freed or unallocated and correspondingly it updates the status.
    = D. All of the above
    ```

<br>
 
17. How many types of Fragmentation are there? 

    ```
    = A. 2
      B. 3
      C. 4
      D. 5
    ```

<br>
 
18. The memory management system must, therefore, allow controlled access to _________________ areas of memory without compromising essential protection. 

    ```
      a) relocated
      b) protected
    = c) shared
      d) organized
    ```

<br>
 
19. _________________ is based on the use of one or both of two basic techniques: segmentation and paging. 

    ```
      a) memory partitioning
    = b) virtual memory
      c) real memory
      d) memory organization
    ```

<br>
 
20. In _________________. there is not necessary to load all of the segments of a process and non-resident segments that are needed are brought in later automatically. 

    ```
      a) Fixed partitioning
      b) Simple Paging
    = c) Virtual memory segmentation
      d) Simple segmentation
    ```

<br>
 
21. In _________________, there is an inefficient use of memory due to internal fragmentation. 

    ```
    = a) Fixed partitioning
      b) Simple Paging
      c) Virtual memory paging
      d) Simple segmentation
    ```

<br>
 
22. In almost all modern multiprogramming systems, the principal operation of memory management involves a sophisticated scheme known as _________________. 

    ```
      a) memory partitioning
    = b) virtual memory
      c) real memory
      d) memory organization
    ```

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>


























**I. User Configuration**

1. Add a user with the username “admin2” and password “currentpass”

   ```
   # useradd -u 210 -g dba -c “Surizal Nazeri” \ -d /home/dc010101 -s /bin/ksh -m dc010101

   Options:
   -u: UID
   -g: GID
   -c: Comment or GCOS
   -d: default initial location when logging in
   -s: Login shell
   -m: ensure create home directory
   ```

   <br>
   
   ```
   sudo adduser admin2
   ```

3. Give the sudo permission to “admin2”
   ```
   sudo usermod -aG sudo admin2
   ```

4. Change the password for “admin2” to “P@ssword”
   ```
   passwd command: change the user’s password

   surizal@dc12345-cmpd153:~$   passwd
   Changing password for surizal.
   (current) UNIX password :
   Enter new UNIX password :
   Retype new UNIX password :
   Passwd:  password updated succesfully
   surizal@dc12345-cmpd153:~$  _

   surizal@dc12345-cmpd153:~$   sudo passwd sn010101
   [sudo] password for surizal :
   Enter new UNIX password :
   Retype new UNIX password :
   Passwd:  password updated succesfully
   surizal@dc12345-cmpd153:~$  _
   ```

   <br>

   ```
   sudo passwd admin2
   ```

5. Insert the details for “admin2” user as follow:
   ```
   i. Name: John Watson
   ii. Office Phone: 0389212020
   iii. Room Number: TA-5-999
   ```
   ```
   sudo usermod -c "John Watson,TA-5-999,0389212020" admin2
   ```

6. Create a new group named as “investigators” with the ID number of “1437”.
   ```
   groupadd command: add group to the system

   # groupadd -g 123 mygroup

   Options:
   -g: GID
   -o: This option permits to add group with non-unique GID
   -r: This flag instructs groupadd to add a system account
   -f: This option causes to just exit with success status, if the specified group already exists. 
   g: If the specified GID already exists, other (unique) GID is chosen
   ```

   <br>

   ```
   sudo groupadd -g 1437 investigators
   ```

7. Add a new user with the username “MonaLisa” with the following details:
   ```
   i. UserID : 369
   ii. Login shell : /bin/sh
   ```
   ```
   sudo useradd -m MonaLisa -u 369 -s /bin/sh
   ```

**II. File and Directory Management**

1. Create a new directory name “Private” under /home/<YourIDNumber> directory.
   ```
   mkdir /home/<YourIDNumber>/Private
   ```

2. Create a new directory name “Family” under /home/<YourIDNumber> directory.
   ```
   mkdir /home/<YourIDNumber>/Family
   ```

3. Create a new directory name “Colleague” under /home/<YourIDNumber>.
   ```
   mkdir /home/<YourIDNumber>/Colleague
   ```

4. Create a new subdirectory name “MyStorage” under “Private” directory.
   ```
   mkdir /home/<YourIDNumber>/Private/MyStorage
   ```

5. Create a new subdirectory name “Tasks” under “Private” directory.
   ```
   mkdir /home/<YourIDNumber>/Private/Tasks
   ```

6. Create a new subdirectory name “FamilyDoc” under “Family” directory.
   ```
   mkdir /home/<YourIDNumber>/Family/FamilyDoc
   ```

7. Create a new directory name “List” under “Colleague" directory.
   ```
   mkdir /home/<YourIDNumber>/Colleague/List
   ```

8. Create a new file name “Mylist.txt” under “<YourIDNumber>” directory. The content of the file should have the list of files and directories at “<YourIDNumber>” directory.
   ```
   ls /home/<YourIDNumber> > /home/<YourIDNumber>/Mylist.txt
   ```

9. Create a new file name “timetable.doc” under “Private” directory. The file should contain the following text: “This is my timetable file for this semester”
   ```
   echo "This is my timetable file for this semester" > /home/<YourIDNumber>/Private/timetable.doc
   ```

10. Create a new file name “Assignment.docx” under “Colleague” directory.
    ```
    touch /home/<YourIDNumber>/Colleague/Assignment.docx
    ```

11. Create a new file name “TaskDate.png” under “Colleague” directory.
    ```
    touch /home/<YourIDNumber>/Colleague/TaskDate.png
    ```

12. Create a new file name “harddisk.txt” under “MyStorage” directory.
    ```
    touch /home/<YourIDNumber>/Private/MyStorage/harddisk.txt
    ```

13. Create a new file name “date.txt” under “FamilyDoc” directory. The file should contain the current date and time. (date command)
    ```
    date > /home/<YourIDNumber>/Family/FamilyDoc/date.txt
    ```

14. Create a new file name “login.txt” under “List” directory. The file should contain the list of users who are currently logged in. (who command)
    ```
    who > /home/<YourIDNumber>/Colleague/List/login.txt
    ```

15. Change the permission for “timetable.doc” so that:
    ```
    • owner can write and execute
    • group can read and execute, and
    • others can only read.
    ```
    ```
    chmod 334 /home/<YourIDNumber>/Private/timetable.doc
    ```

16. Change both the owner and group for the file “date.txt” to root
    ```
    General structure:
    chown <newUser>:<newGroup> <filename>
    ```

    <br>
    
    ```
    sudo chown root:root /home/<YourIDNumber>/Family/FamilyDoc/date.txt
    ```

17. Copy the file “login.txt” to the “Tasks” directory.
    ```
    cp command: copy one or more files or directory structures
    cp <source> <destination>

    $ cp /etc/apt/sources.list /home/surizal
    ```

    <br>
    
    ```
    cp /home/<YourIDNumber>/Colleague/List/login.txt /home/<YourIDNumber>/Private/Tasks/
    ```

18. Archive and compress the “Assignment.docx” and “TaskDate.png” files as an archive file named “NewArchive.tar.gz” at your home directory.

    | **Key options** | **Description**              |
    | :---: | :--- |
    | -c              | Creates an archive           |
    | -x              | Extracts files from archive  |
    | -t              | Displays files in archive    |
    | -v              | Verbose – shows the progress |
    | -f              | Specify archive’s name       |

    -c, -x, -t, cannot be combined with each other.<br>
    -v = optional, but highly advised to used<br>
    -f = COMPULSORY, must specify name of archive<br>
    
    ```
    $ tar –cvzf archive.tar.gz index.html pic2.jpg
    ```

    <br>

    ```
    tar -czvf /home/<YourIDNumber>/NewArchive.tar.gz /home/<YourIDNumber>/Colleague/Assignment.docx /home/<YourIDNumber>/Colleague/TaskDate.png
    ```

20. At your home directory, Copy and extract “NewArchive.tar.gz”
    ```
    cp /home/<YourIDNumber>/NewArchive.tar.gz /home/<YourIDNumber>/
    tar -xzvf /home/<YourIDNumber>/NewArchive.tar.gz -C /home/<YourIDNumber>/
    ```

**III. Package Installation & Configuration**

1. Update and upgrade your server
    ```
   # apt-get update
   # apt-get upgrade
    ```

2. Search the game sgt-puzzles
    ```
    # apt-cache search sgt-puzzles
    ```

3. Install the sgt-puzzles game
    ```
    # apt-get install sgt-puzzles
    ```

<br>**Question 1**

(a) What are the permission for all user category of the files that have permission of 761?

| **Octal** | **String Representation** | **Permissions**        |
| :---: | :---: | :--- |
| 0 (0+0+0) | ---                       | No Permission          |
| 1 (0+0+1) | --x                       | Execute                |
| 2 (0+2+0) | -w-                       | Write                  |
| 3 (0+2+1) | -wx                       | Write + Execute        |
| 4 (4+0+0) | r--                       | Read                   |
| 5 (4+0+1) | r-x                       | Read + Execute         |
| 6 (4+2+0) | rw-                       | Read + Write           |
| 7 (4+2+1) | rwx                       | Read + Write + Execute |

Category<br>
• Owner (user)<br>
• Group<br>
• World (public/everyone/all)

   <br>
   
   ```
   World is only allowed to execute.
   ```

<br>(b) Predict the output for last command in Figure 1.
   ```
   $ WORD1=“ is easy?”
   $ WORD2=“The examination”
   $ WORD3=$WORD2$WORD1
   $ echo $WORD3
   ```
   Figure 1<br>
   ```
   The examination is easy?
   ```

<br>(c) Based on Figure 2, write the correct command (i) until (iii) based on the output stated:-
   ```
   $ ls
   obj01   obj2   obj03   obj04   obj05
   objt1   objt02   objt3   objt04   objt05
   subj1   subj2   subj3   subj14   subj15
   ```

   Figure 2<br><br>

Asterisk (*)<br>
Matches any number of characters including none.

Example:
   ```
   $ ls
   chap   chap01   chap02   chap03   chap04
   chapx  chapy    chapz    draft01  draft02
   $ ls chap*
   chap   chap01   chap02   chap03   chap04
   chapx  chapy    chapz
   ```

<br>

Question Mark (?)<br>
Matches single of character

Example:
   ```
   $ ls
   chap   chap01   chap02   chap03   chap04
   chapx  chapy    chapz    draft01  draft02
   $ ls chap?
   chapx  chapy    chapz
   $ ls chap??
   chap01   chap02   chap03   chap04
   ```

<br>

Rectangular Brackets ([ ])<br>
Matches single of character in the class

Example:
   ```
   $ ls
   chap   chap01   chap02   chap03   chap04
   chapx  chapy    chapz    draft01  draft02
   $ ls chap0[124]
   chap01   chap02   chap04
   $ ls chap0[1-4]
   chap01   chap02   chap03   chap04
   ```

<br>

   (i) obj03   obj04   obj05
   ```
   ls objt0[3-5]
   ```
   <br>(ii) objt02   objt04   objt05
   ```
   ls objt0[245]
   ```
   <br>(iii) subj1   subj2   subj3   subj14   subj15
   ```
   ls subj*
   ```

<br>(d) There are specific commands for all of the following tasks from (i) to (iii). Write a complete and correct command:-
   <br><br>(i) Protect variable VARIABLE1 from being reassigned.
   ```
   $ readonly VARIABLE1
   ```
   <br>(ii) Rename directory1 file as directory2.
   ```
   $ mv directory1 directory2
   ```
   <br>(iii) Delete user danial together with his home directory. 
   ```
   # userdel –r danial
   ```

<br>**Question 2**

(a) Predict the output for the script in Figure 3.
   ```
   $ vi commitment
      #!/bin/bash
      echo "Hi $3"
      echo "You guys are $2"
      echo "I like your $4"
      echo "Thank you for your $0"
      echo "All the best for your $1"
   $ ./commitment final fun everyone focus
   ```
   Figure 3<br>
   ```
   Hi everyone
   You guys are fun
   I like your focus
   Thank you for your commitment
   All the best for your final
   ```

<br>(b) Create a shell script that will display the output as in Figure 4. The script should get a user input and 10 will be added to the input value. Then print the new value. Also, the script will print outputs for some commands.
   ```
   $ final_script
   Welcome to Songs World
   Current User Directory : /home/Azizul

   How many songs do you know? : 15

   The new number is 25

   Malay_lyric.pdf
   English_lyric.txt
   ```
   Figure 4<br><br>
   
   ```
   sudo vi final_script
   ```

   <br>

   You will get a page to write something. To insert some text, please press 'i' and you will see the “INSERT” word at the bottom of the page.

   <br>

   ```
   #!/bin/bash

   echo "Welcome to Songs World"
   echo "Current User Directory : $(pwd)"
   echo
   read -p "How many songs do you know? : " input
   new_value=$((input + 10))
   echo
   echo "The new number is $new_value"
   echo
   touch Malay_lyric.pdf
   touch English_lyric.txt

   echo "Malay_lyric.pdf"
   echo "English_lyric.txt"
   ```

   <br>

   To save, press 'Esc' and 'w' to write and 'q' to quit from “INSERT” mode and press ':' at the keyboard. You need to see ':' at the bottom of your page. Press 'wq' to save and exit. You will get your prompt back.

   <br>

   ```
   sudo chmod +x final_script
   ./final_script
   ```

<br>**I. User Configuration**

1. Add a user with the username “king” and password “current”.
    ```
    sudo adduser king
    ```

2. Give the sudo permission to “king”
    ```
    sudo usermod -aG sudo king
    ```

3. Change the password for “king” to “I@mkinG”
    ```
    sudo passwd king
    ```

4. Insert the details for “king” user as follow:
    ```
    i. Name: Michael
    ii. Office Phone: 039999999
    iii. Room Number: BN-0-04
    ```
    ```
    sudo usermod -c "Michael,BN-0-04,039999999" king
    ```

5. Create a new group named as “royalty” with the ID number of “999”.
    ```
    sudo groupadd -g 999 royalty
    ```

6. Add a new user with the username “Queen” with the following details:
    ```
    i. UserID : 143
    ii. Login shell : /bin/bash
    ```
    ```
    sudo useradd -m Queen -u 143 -s /bin/sh
    ```

<br>**II. File and Directory Management**

1. Create a new directory name Personal under /home directory.
    ```
    $ mkdir /home/Personal
    ```

2. Create a new directory name Family under /home directory.
    ```
    $ mkdir /home/Family
    ```

3. Create a new directory name Friends under /home directory.
    ```
    $ mkdir /home/Friends
    ```

4. Create a new directory name Special under /home directory.
    ```
    $ mkdir /home/Special
    ```

5. Create a new directory name Study under /home/Personal directory.
    ```
    $ mkdir /home/Personal/Study
    ```

6. Create a new directory name Expenditure under /home/Personal directory.
    ```
    $ mkdir /home/Personal/Expenditure
    ```

7. Create a new directory name Cousins under /home/Family directory.
    ```
    $ mkdir /home/Family/Cousins
    ```

8. Create a new directory name Siblings under /home/Family directory.
    ```
    $ mkdir /home/Family/Siblings
    ```

9. Create a new directory name Sem1 under /home/Personal/Study directory.
    ```
    $ mkdir /home/Personal/Study/Sem1
    ```

10. Create a new directory name Sem2 under /home/Personal/Study directory.
    ```
    $ mkdir /home/Personal/Study/Sem2
    ```

11. Create a new file name etc.txt under/ home/ directory. The content of the file should have current date and time.
    ```
    date > /home/etc.txt
    ```

12. Create a new file name result.png under /home/Personal/Study/Sem1 directory.
    ```
    touch /home/Personal/Study/Sem1/result.png
    ```

13. Create two new files under /home/Personal/Expenditure directory. Filenames are:-
    ```
    i) january.xlsx
    ii) february.png
    ```
    ```
    touch /home/Personal/Expenditure/january.xlsx
    touch /home/Personal/Expenditure/february.png
    ```

14. Create two new files under /home/Friends directory. Filenames are:-
    ```
    i) contact.doc
    ii) addresses.txt **contact.doc should contain the following text: “This is the list of contact person.” **Addresses.txt should have list of files and directory at /home directory
    ```
    ```
    echo "This is the list of contact person." > /home/Friends/contact.doc
    ls -la /home > /home/Friends/addresses.txt
    ```

15. Create two new files under /home/Special directory. Filenames are:-
    ```
    i) photo.jpg
    ii) interests.doc
    ```
    ```
    touch /home/Special/photo.jpg
    touch /home/Special/interests.doc
    ```

16. Set the permission of the file result.png under home/Personal/Study/Sem1 directory to be: 
    ```
    • Only the owner can read, write and execute
    ```
    ```
    chmod 700 /home/Personal/Study/Sem1/result.png
    ```

17. Set the permission of the january.xlsx under home/Personal/Expenditure directory to be:
    ```
    • Owner : can read and write only
    • Group : can read and write only
    • World/Others : can read and write only
    ```
    ```
    chmod 666 /home/Personal/Expenditure/january.xlsx
    ```

18. Change both the owner and group for the file etc.txt to root.
    ```
    sudo chown root:root /home/etc.txt
    ```

19. Archive and compress the “photo.jpg” and “interests.doc” files as an archive file named “archive1.tar.gz”.
    ```
    tar -czvf /home/archive1.tar.gz /home/Special/photo.jpg /home/Special/interests.doc
    ```

20. Copy and extract “archive1.tar.gz” to /home directory.
    ```
    cp /home/archive1.tar.gz
    tar -xzvf /home/archive1.tar.gz -C /home/
    ```

<br>**III. Package Installation & Configuration**

1. Update and upgrade your server
    ```
    # apt-get update
    # apt-get upgrade
    ```

2. Search the service postfix
    ```
    # apt-cache search postfix
    ```

<br>**Question 1**

(a) What are the symbol representation for a normal user and superuser?
   - Normal User: $
   - Superuser: #

<br>(b) Predict the output for last command in Figure 1.
   ```
   $ SENT1=“is virtue”
   $ SENT2=“patience”
   $ SENT3=$SENT1$SENT2
   $ echo $SENT3
   ```
   Figure 1<br>
   ```
   is virtuepatience
   ```

<br>(c) Based on figure below, answer the following set of questions.

```
ikhsan@dc99999-server:~$ ls -l
total 84
-rw-rw-r-- 1 ikhsan ikhsan 15 Mar 21 07:44 aaa.doc
-rw-rw-r-- 1 ikhsan ikhsan 17 Nov 30 03:53 abc.txt
-rw-rw-r-- 1 ikhsan ikhsan 0 Mar 21 05:19 abc.xlsx
-rw-rw-r-- 1 ikhsan ikhsan 5 Mar 21 07:32 addresses.txt
drwxrwxr-x 5 ikhsan ikhsan 4096 Nov 1 05:18 dc123456
drwxrwxr-x 2 ikhsan ikhsan 4096 Nov 1 04:30 examdemo
-rw-rw-r-- 1 ikhsan ikhsan 0 Nov 30 03:51 index.html
-rw-rw-r-- 1 ikhsan ikhsan 0 Oct 3 04:32 marks.xls
-rw-rw-r-- 1 ikhsan ikhsan 10240 Oct 17 01:43 myarchive.tar
drwxrwxr-x 2 ikhsan ikhsan 4096 Nov 14 02:44 mybackup
-rwxrwxrwx 1 root root 90 Nov 14 02:07 my first
drwxrwxr-x 2 ikhsan ikhsan 4096 Oct 17 01:44 myfolder
```
   Figure 2<br><br><br>
(i) Identify the type of permissions for myfolder.
   - Read and execute permission for all users. The owner and group also has write permission.

<br>(ii) What is the type of files for abc.txt?
   - Regular file

<br>(iii) Elaborate on the command that are used in Figure 2.
   - The `ls -l` command is used to list files and directories with detailed information, including permissions, owner, group, size, modification time, and name.

<br>(iv) Identify how many directory files can be found in Figure 2.
   - dc123456, examdemo, mybackup, and myfolder.

<br>(d) There are specific commands for all of the following tasks from (i) to (iii). Write a complete and correct command:-

<br>(i) View history of commands executed earlier with the sentence ‘boot’ as part of the command.
   ```
   history | grep boot
   ```

<br>(ii) View test.txt file which are in the directory /home/folder1/subfolder1.
   ```
   cat /home/folder1/subfolder1/test.txt
   ```

<br>(iii) Delete user alyph together with his home directory.
   ```
   # userdel –r alyph
   ```

<br>**Question 2**

(a) Predict the output for the script in Figure 3.
   ```
   $ vi commitment
      #!/bin/bash
      echo "Greetings $3"
      echo "Today is $2"
      echo "So there will be no $1"
      echo "Enjoy your $0"
      echo "See you next $4"
   $ ./holiday assessment Friday everyone week
   ```
   Figure 3<br>
   ```
   Greetings everyone
   Today is Friday
   So there will be no assessment
   Enjoy your holiday
   See you next week
   ```

<br>(b) Create a shell script that will display the output as in Figure 4. The script should display current user who’s using the system, get a user input and 10 will be deducted from the input value and will be printed. The script will also displays various files of different extensions.

   ```
   $ test_scripting
   Welcome to My Second Script
   I am logged in as : User

   What is your favorite number? : 99

   After subtracting with 10, the number will be : 89

   Fav_number.png
   Fav_food.txt
   Fav_drink.doc
   ```
   Figure 4<br><br>
Create a script named `test_scripting` with the following content:

```
#!/bin/bash

echo "Welcome to My Second Script"
echo "I am logged in as : $(whoami)"
echo
read -p "What is your favorite number? : " input
result=$((input - 10))
echo
echo "After subtracting with 10, the number will be : $result"
echo
echo "Fav_number.png"
echo "Fav_food.txt"
echo "Fav_drink.doc"
```

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

Lab 1.1:
```
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
}
```
<br>




Lab 1.2:
```
void setup() {
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(250);
  digitalWrite(13, LOW); 
  delay(250);
  digitalWrite(12, HIGH);
  delay(250);
  digitalWrite(12, LOW);
  delay(250);
  digitalWrite(11, HIGH);
  delay(250);
  digitalWrite(11, LOW); 
  delay(250);
}
```
<br>




Lab 1.2.1:
```
void setup() {
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
  pinMode(10, OUTPUT);
}

void loop() {
  kelip(13);
  kelip(12);
  kelip(11);
  kelip(10);
}

void kelip(int pin) {
  digitalWrite(pin, HIGH);
  delay(250);
  digitalWrite(pin, LOW);
  delay(250);
}
```
<br>




Lab 1.3:
```
void setup() {
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
}

void loop() {
  kelip(13, 2000);
  kelip(12, 500);
  kelip(11, 1500);
}

void kelip(int pin, int masa) {
  digitalWrite(pin, HIGH); 
  delay(masa); 
  digitalWrite(pin, LOW);
}
```
<br>




Lab 1.4:
```
void setup() {
  tone(7, 262, 250);
  delay(250 * 1.30);
  tone(7, 196, 125);
  delay(125 * 1.30);
  tone(7, 196, 125);
  delay(125 * 1.30);
  tone(7, 220, 250);
  delay(250 * 1.30);
  tone(7, 196, 250);
  delay(250 * 1.30);
  tone(7, 247, 250);
  delay(250 * 1.30);
  tone(7, 247, 250);
  delay(250 * 1.30);
  tone(7, 262, 250);
  delay(250 * 1.30);
}

void loop() {
}
```
<br>




Lab 2.1:
```
int red = 9;

void setup() {
  pinMode(red, OUTPUT);
}

void loop() {
  analogWrite(red, 0);
  delay(1000);
  analogWrite(red, 10);
  delay(1000);
  analogWrite(red, 20);
  delay(1000);
  analogWrite(red, 30);
  delay(1000);
  analogWrite(red, 40);
  delay(1000);
}
```
<br>




Lab 2.2:
```
void setup() {
  pinMode(9, OUTPUT);
  pinMode(10, OUTPUT);
  pinMode(11, OUTPUT);
}

void loop() {
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 262, 250);
  delay(250 * 1.30);
  
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 196, 125);
  delay(125 * 1.30);
  
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 196, 125);
  delay(125 * 1.30);
  
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 220, 250);
  delay(250 * 1.30);
  
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 196, 250);
  delay(250 * 1.30);
  
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 247, 250);
  delay(250 * 1.30);
  
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 247, 250);
  delay(250 * 1.30);
  
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 262, 250);
  delay(250 * 1.30);
}
```
<br>




Lab 3.0:
```
void setup() {
  pinMode(9, INPUT);
  pinMode(5, OUTPUT);
}

void loop() {
  if (digitalRead(9) == HIGH) {
    digitalWrite(5, HIGH);
  } else {
    digitalWrite(5, LOW);
  }
}
```
<br>




Lab 4.1:
```
void setup() {
  Serial.begin(9600);
}

void loop() {
  int Dout = analogRead(A0);
  float Vin = Dout * 0.00488;
  Serial.print("voltage: ");
  Serial.println(Vin);
  delay(100);
}
```
<br>




Lab 4.2:
```
void setup() {
  pinMode(9, OUTPUT);
}

void loop() {
  int pot = analogRead(A0);
  pot = map(pot, 0, 1023, 0, 255);
  analogWrite(9, pot);
}
```
<br>




Lab 4.3:
```
int LDR_Pin = A0; //analog pin A0

void setup() {
  Serial.begin(9600);
  pinMode(2, OUTPUT);
}

void loop() {
  int LDRReading = analogRead(LDR_Pin);
  float Vout = LDRReading * 0.00488; //Convert readings to voltage
  Serial.println(Vout);
  delay(250); //just here to slow down the output for easier reading
  if (Vout > 1.0) {
    digitalWrite(2, HIGH);
  } else {
    digitalWrite(2, LOW);
  }
}
```
<br>




Lab 4.4:
```
void setup() {
  Serial.begin(9600);
}

void loop() {
  int Dout = analogRead(A0);
  float Vin = Dout * 0.00488;
  float temp = Vin * 100;
  Serial.println(temp);
  delay(100);
}
```
<br>




Lab 5.1:
```
#include <LiquidCrystal.h>
LiquidCrystal lcd(8, 9, 10, 11, 12, 13); //RS, EN, D4, D5, D6, D7

void setup() {
  lcd.begin(16, 2);
  lcd.print("hello, world!");
}

void loop() {
  lcd.setCursor(0, 1);
  lcd.print(millis() / 1000);
}
```
<br>




Lab 5.2:
```
#include <SimpleDHT.h>
int pinDHT11 = 2;
SimpleDHT11 dht11(pinDHT11);

void setup() {
  Serial.begin(9600);
}

void loop() {
  //start working..
  Serial.println("Sample DHT11...");
  //read without samples.
  byte temperature = 0;
  byte humidity = 0;
  //read temperature and humidity value to PC.
  Serial.print("Sample OK: ");
  Serial.print((int)temperature); 
  Serial.print(" C, ");
  Serial.print((int)humidity); 
  Serial.println(" H");
  //DHT11 sampling rate is 1HZ.
  //it is a must to have this delay when working DHT11.
  delay(1500);
}
```
<br>




Lab 5.3:
```
#include <Wire.h>
#include "RTClib.h"
RTC_DS1307 RTC;

void setup() {
  Serial.begin(9600);
  Wire.begin();
  RTC.begin();
  if (!RTC.isrunning()) {
    Serial.println("RTC is NOT running!");
    // This will reflect the time that your sketch was compiled
    RTC.adjust(DateTime(__DATE__, __TIME__));
  }
}

void loop() {
  DateTime now = RTC.now();
  Serial.print(now.month(), DEC);
  Serial.print('/');
  Serial.print(now.day(), DEC);
  Serial.print('/');
  Serial.print(now.year(), DEC);
  Serial.print(' ');
  Serial.print(now.hour(), DEC);
  Serial.print(':');
  Serial.print(now.minute(), DEC);
  Serial.print(':');
  Serial.print(now.second(), DEC);
  Serial.println();
  delay(1000);
}
```
<br>




Lab 6.1:
```
```
<br>




Lab 6.2:
```
```
<br>




<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

Maybank Malaysia Berhad wants to develop a new mobile application (app) dedicating to fund investment. Maybank hires IBM Malaysia to develop the app for them. Maybank Malaysia Berhad is known as _____.

```
   A. people
 = B. system owner
   C. system developer
   D. users
```

<br>

Astro is in the process of collecting information about its customers' details. They want to conduct an analysis about their customers' demographics such as age, gender and income. They send out emails with link to online survey to all of their customers. For all answered questionnaire, the customer will receive a gift voucher.<br>

Which of the followings is data? 

```
   A. surveys sent to customers
 = B. survey answered by customers
   C. analyzed data about customers' demographics
   D. gift vouchers
```
<br>

Which of the followings is information? 

```
   A. survey answered by customers
 = B. analyzed data about customers' demographics
   C. gift vouchers
   D. surveys sent to customers
```

<br>

Rasa Sayang Hotel wants to modify its registration system. Ali, the Director of Customer Service Department noticed that the existing system does not cater for giving points for repeating customers. Ali recommends that by giving points which can be transferred to a discount voucher will attract more repeating customers. So, Ali pitched this idea to the hotels' IT team. However, the IT team is not able to modify the current system as they are just focusing at the technical aspects of the computers and network. Because of that, Rasa Sayang Hotel decided to pass the project to Teknologi Malaysia Sdn Bhd.

Which type of hardware will be used for this information system?

```
   A. tablets
 = B. workstations
   C. mobile phones
   D. smart TVs
```

<br>

Which software source is applied?

```
   A. In-house development
 = B. IT Services Firm
   C. Enterprise Solutions Software
   D. Cloud Computing 
```

<br>

<br>

Enterprise solution software is combination of many softwares for a specific company. 

```
 = True
   False
```

<br>

Tools are typically computer programs that make it easy to use and benefit from techniques and to faithfully follow the guidelines of the overall development methodology.

```
 = True
   False
```

<br>


Maybank Malaysia Berhad wants to develop a new mobile application (app) dedicating to promote their services. Maybank hires IBM Malaysia to develop the app for them. Maybank Malaysia Berhad wants the app to send out flyers, advertisements and notifications to their customers. This project is known as a/an _______ project.

```
   A. open source 
   B. financial
   C. in-house
 = D. outsource
```

<br>

Which of the following methodology is suitable for clients that are eager to be a part of the development process?

```
   A. System Development Life Cycle
   B. Object Oriented Application Development
   C. Rapid Application Development
 = D. AGILE
```

<br>

It is important to involve only certain stakeholders in the requirements gathering process. 

```
   True
 = False
```

<br>

The primary purpose of using JAD in the analysis phase is to collect systems requirements simultaneously from the key people involved with the system.

```
 = True
   False
```

<br>

**Prepare a Functional Decomposition Diagram(FDD) based on the case scenario given below. You need to draw the FDD on a piece of paper. Take photo of your work and save as JPEG, JPG, GIF, BMP, PNG or PDF. Upload the file in the given area here.** <br>

**Case scenario** <br>

You had interviewed Mr Tahir Suhaimi who is the Operation Senior Manager, ITMS, UNITEN. From the interview session, these are the details you gathered about the classrooms booking process. Change the details by structuring the requirements using FDD (swimlane flowchart).<br>

1. Lecturers make their bookings using the booking system online. Lecturers need to login into the system.<br>
2. Lecturers need to first identify the date and timeslot for class. The system will display a selection of available classrooms. However, if there are no available classrooms, the system will ask the lecturers to choose another date and timeslot or end the process.<br>
3. Lecturers must accept only one option. A notification will be sent to lecturers as successful booking.<br>
4. For all successful booking, the technician will receive the same notification. The technician has to make sure the classrooms are in working order. If there is any problem, the technician can cancel the booking, and a notification will be sent to the lecturers. If there is no problem, a virtual key will be given to lecturers to use the classrooms.<br>
5. Once lecturers complete using the classrooms, lecturers need to end the booking process by pressing the COMPLETE button in the system.<br>

![Slide1](https://github.com/Tallyobin/One-More-Door/assets/156051265/c173dc00-d5c7-41b3-a0d4-3e2702a795b6)<br>

Comment: your numbering are wrong for all of your subprocesses/subtasks.

<br>

Which phase of the SDLC is responsible for developing the system components and code?

```
   a. Analysis
 = b. Implementation
   c. Design
   d. Planning
```

<br>

Which of the following is **NOT** a project initiation activity?  

```
   a. Establishing a relationship with the customer.  
   b. Establishing the project duration, start and end dates.
   c. Establishing the project initiation team. 
 = d. Dividing the project into manageable tasks. 
```

<br>

Which of the following is **NOT** a phase of the system development life cycle (SDLC)?

```
   a. System design.
 = b. System development.
   c. System Implementation.
   d. System Maintenance.
```

<br>

Which of the following is **NOT** a benefit of using a structured SDLC methodology?

```
 = a. Increased cost and schedule overruns.
   b. Improved system quality and maintainability.
   c. Reduced risk of errors and defects.
   d. Improved communication and collaboration between team members.
```

<br>

An assessment of the development group's understanding of the possible target hardware, software, and operating environments, system size, complexity, and the group's experience with similar systems should be included as part of ___ feasibililty. 

```
   a. economic
 = b. technical
   c. operational
   d. legal
```

<br>

Project: To develop UNITEN new website<br>

| Identifier | Tasks | Predecessor | Duration (months) |
|------------|-------|-------------|-------------------|
| A | Prepare proposal | - | 2 |
| B | Approve Proposal | A | 1 |
| C | Decision Making for in-house/outsource | B | 1 |
| D | List all functionalities & requirements | - | 3 |
| E | Prepare Project Charter, BPP and PSS | C, D | 1 |
| F | Start System Development | E | 3 |
| G | Testing and Installation | F | 1 |

*Set your duration column on monthly basis.<br>

Based on the WBS shown, **draw a gantt chart** on a piece of paper. Once done, take a photograph of your answer (make sure it is clear and readable), and upload the image/file into the area specified.  The image should either be jpg, jpeg, gif, png or pdf only.<br>

Assuming this project starts on 4th December 2023 (Friday), **how long is this project in total** and **when is the end date of this project?** <br>

![Gantt](https://github.com/Tallyobin/One-More-Door/assets/156051265/369c019b-d86d-4b15-babb-af8beb4472e3)<br>

Comment: end date - 3 sept 2024

<br>

Identify the **CORRECT** economic feasibility category for each of these statements.<br>

**Competitive advantage**: Marrybrown's new supply chain management (SCM) system can help businesses improve their inventory management and order fulfillment processes, which can lead to lower costs and faster delivery times for customers.

```
Tangible benefits,
```

<br>

**Lost productivity**: Marrybrown employees may need to be diverted from their regular work duties to participate in the development and implementation of the new system. This can lead to lost productivity and decreased efficiency.

```
intangible cost,
```

<br>

**Hardware costs**: The cost of the hardware required to run the new CRM system, such as servers, workstations, and network equipment.

```
tangible cost, one-time,
```

<br>

**Testing and deployment costs**: Once Marrybrown app is developed, it needs to be tested thoroughly to ensure that it is free of bugs and meets the needs of users. The cost of testing depends on the number of testers and will be conducted for 6 months.

```
Tangible cost, recurring, variable,
```

<br>

**Maintenance and support costs**: Marrybrown spends $50,000 per year on maintaining and supporting a new customer relationship management (CRM) system.

```
Tangible cost, recurring, fixed,
```

<br>

**Improved customer service**: Marrybrown's new customer relationship management (CRM) system helps businesses to track customer interactions and preferences, which can lead to more personalized and responsive customer service.

```
Intangible benefits
```

<br>

During requirements determination, information can be gathered from users of the current system, forms, reports, and procedures.

```
 = True
   False
```

<br>

**Case study** <br>

CIMB Malaysia now offers digital banking services through their CIMB Clicks Mobile App (formerly CIMB EVA) for their current cardholders. This app is their portal that lets you check your account balance, view transaction history, transfer money, purchase online, and pay bills and loans.<br>

Their app also lets you top up your credit and start investing through their e-IPO, ASNB, Travel Currency, and more. This ensures that your investment platform is safe and secured from malware or hacking.<br>

CIMB Clicks Mobile App has FaceID & TouchID feature that lets you log in without typing your username or password which is pretty convenient when you’re paying using QR. Because this digital app is new, they feature a “Revamped’ home screen that is more user-friendly than the previous app.<br>

In case you don’t have a CIMB account yet, you can just visit their website and apply for an account online. Also, if you are a Samsung user, CIMB has a Partner Pay Solution with them that purchases from numerous retail stores in Malaysia. <br>

**You are required to come up with a SSR (system service request). Answer ALL of these FOUR questions by typing your answers here in Brighten.** <br>

**Questions** <br>
1. Identify what is the information system mentioned in the case study. [1m]<br>
2. Identify SIX (6) functionalities (business processes) mentioned in the case study. [6m]<br>
3. Identify the expected value from the information system mentioned in the case study (1 - tangible benefit and 1 intangible benefit) [2m]<br>
4. List one (1) special issue/constraint identified from the case study. [1m]<br>

```
System Service Request (SSR): CIMB Clicks Mobile App Enhancement

1. CIMB Clicks Mobile App

2. Check account balance, view transaction history, transfer money, purchase online, pay bills and loans, invest through e-IPO, ASNB. 

3.
Tangible Benefit: Enhanced Security: FaceID & TouchID features ensure secure logins, protecting users from unauthorized access and potential financial risks.
Intangible Benefit: Improved User Experience: The "Revamped" home screen contributes to a more user-friendly interface, enhancing overall user satisfaction and engagement.

4. Ensuring the security and integrity of user data and financial transactions, especially with the implementation of advanced features like FaceID & TouchID. 
```

Comment: Q3a - must state in numbers or %

<br>

Which system methodology is most widely used?

```
   a. RAD
   b. Agile
   c. OOAD
 = d. SDLC
```

<br>

Which methodology is best suited for projects with rapidly changing requirements?

```
   a. Prototyping
   b. OOAD
   c. SDLC
 = d. Agile
```

<br>

Prepare a context diagram based on these details.<br>

LAZADA is one of the Malaysia’s biggest online clothing trading companies. With LAZADA, it allows different users to work within the system for different purposes. LAZADA customers could order their preferred clothes and receive receipt for the purchases made. Clothes supplier could access the clothes order and send receipt to the customer who bought their products through LAZAD   A.  At the same time, clothes stores will accept the clothes order to process for shipment. At the end of each month, all data of the sales made in LAZADA will be compiled and management reports will be prepared based on those dat   a.  These management report will be sent to Sales Manager.<br>

Upload your diagram here. You may save it as pdf, png, gif, jpe, jpg, or jpeg.<br>

![20231220_200904](https://github.com/Tallyobin/One-More-Door/assets/156051265/ad77ad1f-3ffd-4eba-9d4d-75b3bc0e33f5)

<br>

How many external entities identified?

```
   A. 3
   B. 5
 = C. 4
   D. 2
```

<br>

For external entity **clothes stores**, which type of entity is it?

```
 = A. Sink
   B. Source
   C. Entity
   D. Source & sink
```

<br>

**Management report/s** is/are known as _______ to a context diagram.

```
 = A. output
   B. sink
   C. input
   D. report
```

<br>

For external entity **customer**, which type of entity is it?

```
   A. Sink
   B. Source
 = C. Source & Sink
   D. Entity
```

<br>

When designing a form, for data entry, users should be required to enter the current date and time.

```
   True
 = False
```

<br>

A normal conversation is a method by which users interact with information systems.

```
   True
 = False
```

<br>

A highly intuitive human-computer interaction method where data fields are formatted in a manner similar to paper-based forms is known as ______.

```
   A. object-based interaction
 = B. form interaction
   C. human computer interaction
   D. menu interaction
```

<br>

This type of menu positioning method places the access point of the menu near the top line of the display; when accessed, menus open by dropping down onto the display.

```
   A. pop-up menu
   B. listed menu
   C. list of option
 = D. drop-down menu
```

<br>

 A human-computer interaction method where inputs to and outputs from a computer-based application are in a conventional spoken language such as English refers to as ______.

```
 = A. natural language interaction
   B. command line interaction
   C. English language interaction
   D. command based interaction
```

<br>

A method by which users interact with information systems defines ______.

```
   A. method
   B. dialogue
 = C. interface
   D. interaction
```

<br>

Commonly used methods for highlighting include each of the following EXCEPT ______. 

```
   A. spacing
   B. all capital letters
   C. boxing
 = D. underlining
```

<br>

Using lists to break information into manageable pieces conforms to the SOS guideline or report is known as ______.

```
 = A. organize
   B. shortcuts
   C. chaos
   D. simplicity
```

<br>

Interface design focuses on _____.

```
 = A. how information is provided and captured from users
   B. the design of forms and reports
   C. how to connect to system files and databases
   D. turning design specifications into working computer code
```

<br>

System feedback provides status information, prompting cues, and error or warning messages.

```
 = True
   False
```

<br>

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>  

```
Why to use Files
• Convenient way to deal large quantities of data.
• Store data permanently (until file is deleted).
• Avoid typing data into program multiple times.
• Share data between programs.


9. Which of the following is NOT describe about a structure?
   A. We can have pointers of type structures.
   B. Defining a structure is like defining a new data type.
   C. A structure may contain members of many data types.
 = D. A structure may contain function as members of its elements.

Structure can have a member and a class*


10. Which of the following is a properly defined struct?
    A. struct { int x; }
    B. struct my_struct int x;
    C. struct my_struct{ int x; }
 = D. struct my_struct{ int x; };

Must have a semicolon ";" and curly braces "{ }"


11. Which symbol is used to define the member of a class externally?
    A. :
    B. #
    C. ::
 = D. };


12. Which of the following is declare just like a regular member function, but with a name that matches the class name and without any return type?
    A. Cass
    B. Object
  = C. Constructor
    D. User-defined

Constructor is named the same as the class and don't have a data type*


14. When constructor is invoked automatically?
    A. A class is defined.
    B. A class is referenced.
  = C. An object is instantiated.
    D. An object is called by a function.


15. What will be the output if the string syafiqah is entered in code Figure 1?

    Char name[20];
    cout << “Enter your name : ” ;
    cin.width(5);
    cin >> name;
    cout << name << endl;

    Figure 1

    A. syaf
  = B. syafi
    C. syafiq
    D. syafiqah


16. Which stream manipulator forces a floating point number to display a specific number of digits to the right of the decimal point?
  = A. fixed
    B. setw()
    C. width()
    D. scientific


17. Which stream manipulator is used to reset function showpos back to default display mode?
  = A. noshowpos
    B. stopshowpos
    C. cancelshowpos
    D. removeshowpoint


18. Which stream manipulator forces a floating point number to be output with its decimal point and trailing zeros?
    A. showcase
  = B. showpoint
    C. showarray
    D. noshowpoint


19. Which class file handle both file input and output?
    A. infile
    B. outfile
  = C. fstream
    D. ofstream


20. What does it mean by ofstream in C++?
    A. Delete the file.
  = B. Writes to a file.
    C. Reads from a file.
    D. Writes to a file & Reads from a file.


12. Which the following is used to call function within a class?
    A. Member
    B. Operator
    C. Class
  = D. Method


14. All of the following is a valid access specifier in a class EXCEPT:
    A. private
    B. public
    C. protected
  = D. encapsulated


15. How many times a derived class can inherit from a base class?
    A. One
    B. Maximum three
    C. Maximum five
  = D. More than one
```











```
(a)
(i) Account
(ii) Public and it can be accessed by all.
(iii) MyBal
(iv) To call the function displayTotalBalance.
(v) You may click here for total balance









Volume of Box1 : 210.0
Volume of Box2 : 240.0

210.0 * 12



Question 7

struct committee {

   string fullname;
   int year;
   float cgpa;
   string designation;
};


Struct committee  com1;
cout << com1.fullname;
cout << com1.year;
cout << com1.cgpa;
cout << com1.designation;







# include < iostream>
# include <fstream>
using namespace std;


Int main ( )
{
   int odd=0, oddTotal=0, sum=0;
   Instream infile;
   Infile.open("integer.txt")






while(infile>n)
{
   if(n/2!=0)
   {
      odd++;
      oddTotal=oddTotal+n;
   }
   sum=sum+n;
}
ofstream outfile;
outfile.open("odd.txt");





outfile << "Total of odd number : " << odd << endl;
outfile << "Summation of odd number : " << oddTotal << endl;


cout << "The total of all numbers : " << sum;












#include <iostream>
using namespace std;

class Movie {
   private
      string title;
      int year;
      float income.profit;
      string BoxOfficeStandard;

public:
Movie ( ) {
    cout << "Enter the Title Movie : ";
   getline (Cin,title);
    cout << "Enter the Year of Movie Lanveh : ";
   cin >> year;
   cout << "Enter the profit of the movie (USD) : ";
   cin >> income_profit;
}

void report ( ) {
   cout << "Movie title" << title << "produce in
   the year" << year << " is a " << BoxOfficeStatus;




void get BoxOfficeStatus ( )
{ 
   if (income_profit > 50,000 oou)
      return " Box Office";
   else 
      return "flop";
}
},




int main ( )
{
   Movie m1;
   m1.report;
}
```

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

**Question 1**<br>
Performance and abilities of disk input/output (I/O) operation depends on several factors; computer system architecture, operating system and disk control hardware.

(a) In disk scheduling, performances among various scheduling policies varies due to difference of value for seek time. What does seek time means? **[1 mark]** <br>

The time it takes to position the head at the track

<br>

(b) Label A, B and C accordingly. **[3 marks]**

![Untitled328_20240128020758](https://github.com/Tallyobin/Searchlight-Division/assets/156051265/587e6f12-178d-4e8c-8de3-b024e3860080)

Figure 1 – Disk <br><br>

![Untitled328_20240128023630](https://github.com/Tallyobin/Searchlight-Division/assets/156051265/0364b8a2-a919-476e-939c-35d3e9caf83b)

<br>

(c) There are **FOUR (4)** common disk scheduling policies commonly used; First in First Out (FIFO), Shortest Seek Time First (SSTF), SCAN and C-SCAN.<br>

Consider the following set of information:-<br>
Disk track request : 20, 30, 50, 90, 70, 160, 180, 60, 10<br>
Initial Head location : Track 100<br>
Head movement : Increasing

<br>

(d) Employ **SSTF**, **SCAN** and **FIFO** scheduling policies accordingly and show all the necessary track movements. **[12 marks]** <br>

SSTF (Shortest Seek Time First), SCAN, and FIFO (First In First Out) scheduling policies can be applied to the given disk track requests with an initial head location at Track 100 and head movement in the increasing direction.

Here is the step-by-step track movement for each scheduling policy:

1. **SSTF (Shortest Seek Time First):**
   - Head movement: 90, 70, 60, 50, 30, 20, 10, 160, 180

2. **SCAN:**
   - Head movement: 160, 180, 90, 70, 60, 50, 30, 20, 10

3. **FIFO (First In First Out):**
   - Head movement: 20, 30, 50, 90, 70, 160, 180, 60, 10

These movements represent the order in which the disk arm accesses the specified tracks according to each scheduling policy.

<br><br>

**Question 2**<br>
Scheduling is one of the key that leads to multiprogramming on OS environment. There are FOUR(4) types of process scheduling commonly involved in OS.

(a) List down all types of scheduling. **[4 marks]** <br>

  1. **Long-Term Scheduling**
  2. **Medium-Term Scheduling**
  3. **Short-Term Scheduling**
  4. **I/O Scheduling**

<br>

(b) Fill in the table accordingly on the specific types of scheduling based on the explanation. **[2 marks]**

| Types of Scheduling        | Explanation                                                                                         |
|----------------------------|-----------------------------------------------------------------------------------------------------|
| Long-Term Scheduling       | The decision to add to the pool of processes to be executed.                                        |
| Medium-Term Scheduling     | The decision to add to the number of processes that are partially or fully in main memory.          |
| Short-Term Scheduling      | The decision as to which available process will be executed by the processor.                       |
| I/O Scheduling             | The decision as to which process’s pending I/O request shall be handled by an available I/O device. |

Table 1 – Scheduling type

<br>

(c) There are several scheduling policies that are commonly employed by the operating system in order to determine which processes will be chosen for execution.

i. There are **TWO (2)** decision modes commonly used on uniprocessors’ scheduling. Name both of them. **[2 marks]** <br>

   1. **Nonpreemptive**
   2. **Preemptive**

<br>

ii. Draw the scheduling diagram for the information provided in Table 2 by employing Highest Response Ratio Next (HRRN) scheduling policies. Calculate the average waiting time as well. **[11 marks]**

| Process | Arrival Time | Service Time |
| :---    | :---         | :---         |
| J       | 1            | 4            |
| K       | 2            | 2            |
| L       | 5            | 3            |
| M       | 8            | 6            |
| N       | 9            | 4            |

Table 2 - Set of Processes

<br>

| J | K | L | M | N |
|---|---|---|---|---|

1   5   7   10  16  20


at T5 = K & L have arrived

```
RRK = ((5 - 2) + 2) / 2
    = (3 + 2) / 2
    = 5 / 2
    = 2.5

RRL = ((5 - 5) + 3) / 3
    = 3 / 3
    = 1
```
    
at T10 = M & N have arrived

```
RRM = ((10 - 8) + 6) / 6
    = (2 + 6) / 6
    = 8 / 6
    = 1.33

RRN = ((10 - 9) + 4) / 4
    = (1 + 4) / 4
    = 5 / 4
    = 1.25
```

<br><br>

**Question 3**

(a) Consider the following system state which are made up of 4 processes and 4 resources shown in Figure 2.

<br>

| a | b | c | d |
|---|---|---|---|

Resource Vector

<br>

| 0 | 1 | 0 | 1 |
|---|---|---|---|

Available Vector

<br>

| 1 | 2 | 3 | 4 |
|---|---|---|---|
| 2 | 2 | 5 | 1 |
| 2 | 1 | 2 | 1 |
| 4 | 3 | 1 | 2 |

Max Matrix

<br>

| 1 | 1 | 1 | 1 |
|---|---|---|---|
| 1 | 2 | 3 | 1 |
| 2 | 0 | 2 | 1 |
| 3 | 2 | 1 | 1 |

Allocation Matrix

<br>

Figure 2

<br>

(i) Find the Need Matrix **[1 mark]** <br>

The Need Matrix is calculated as the difference between the Max Matrix and the Allocation Matrix.<br>

Need = Max - Allocation<br>

```
| 1 | 2 | 3 | 4 |   | 1 | 1 | 1 | 1 |
|---|---|---|---|   |---|---|---|---|
| 2 | 2 | 5 | 1 | - | 1 | 2 | 3 | 1 |
| 2 | 1 | 2 | 1 |   | 2 | 0 | 2 | 1 |
| 4 | 3 | 1 | 2 |   | 3 | 2 | 1 | 1 |
```

<br>

```
| 0 | 1 | 2 | 3 |
|---|---|---|---|
| 1 | 0 | 2 | 0 |
| 0 | 1 | 0 | 0 |
| 1 | 1 | 0 | 1 |
```

<br>

(ii) Is the system state is in currently safe or unsafe state? Show your working steps / calculation and justify your answer. **[3 marks]** <br>

| 0 | 1 | 0 | 1 |
|---|---|---|---|

Available Vector

<br>

| 0 | 1 | 2 | 3 |
|---|---|---|---|
| 1 | 0 | 2 | 0 |
| 0 | 1 | 0 | 0 |
| 1 | 1 | 0 | 1 |

Need Matrix

<br>

For process P0, Need = (0, 1, 2, 3) and Available = (0, 1, 0, 1)<br>
Need <= Available = False

<br><br>

**Question 4**

(a) State **ONE (1)** example of human readable and **ONE (1)** example of machine readable I/O device. **[3 marks]** <br>

- **Human Readable I/O Device Example:** Keyboard
- **Machine Readable I/O Device Example:** Controllers

<br>

(b) There are **THREE (3)** main techniques for performing I/O process. List all of them. **[3 marks]** <br>

1. **Programmed I/O**
2. **Interrupt-driven I/O**
3. **Direct memory access (DMA)**

<br><br>

**Question 5**<br>
Deadlocks occur generally because processes deny each other’s’ resources and none can proceed to completion. It is a permanent occurrence that cannot be solved efficiently. In general, there are several ways or strategies to be dealing with deadlock. One of the ways to show a deadlock representation is by using resource allocation graphs.<br>

Processes: PA, PB, PC, PD<br>
Resources: R1 (3units), R2 (2 units), R3 (2 units), R4 (3 units)<br>
Requirements: Processes needs to have 3 different resources before it can be executed / completed.<br>

Draw a Resource Allocation Graph that represents information shown above. **[10 marks]** <br>

![Screenshot_170](https://github.com/Tallyobin/Searchlight-Division/assets/156051265/678b1105-ede9-4bf1-bead-d12a62f975e8)

<br><br>

**Question 6**

(a) The prime purpose of memory management is to ready programs into memory for execution by the processor. Without using virtual memory, there are a few main techniques could be used; partitioning, simple paging and simple segmentation.

(i) What do you understand on the concept of partitioning? **[1 mark]** <br>

**Partitioning is an early method of managing memory.**

<br>

(ii) There are two types of fragmentation that could happen when partitioning technique is being carried out. Name both of the fragmentations, and list down **TWO (2)** differences between both types of fragmentations. **[6 marks]** <br>

1. **Internal Fragmentation:**
   - Occurs when memory allocated to a process is larger than the actual memory required.
   - The unused memory within a partition is wasted.
   - More common in Fixed Partitioning.

2. **External Fragmentation:**
   - Occurs when free memory blocks are scattered throughout the memory, but the total free space is sufficient to satisfy a request.
   - Leads to inefficient use of memory.
   - More common in Dynamic Partitioning.

Differences:
   - Internal fragmentation is caused by the allocated memory being larger than needed, while external fragmentation is caused by scattered free memory blocks.
   - Internal fragmentation is inherent to Fixed Partitioning, while external fragmentation is more prominent in Dynamic Partitioning.

<br>

(b) Page Replacement Policy is used to decide on the selection of page in main memory to be replaced when a newer page is brought in.

(i) Name **TWO (2)** algorithms that are commonly used in page replacement policy. **[2 marks]** <br>

1. **Optimal**
2. **Least recently used (LRU)**

<br>

(ii) Given the following information:-<br>
Resident Set = 3 frames, Page address stream: - | 2 | 3 | 4 | 2 | 1 | 3 | 7 | 5 | 4 | 3 |<br>
By using any **ONE (1)** of the algorithms mentioned in Question (b) (i), draw a table that shows the page placement correctly. **[5 marks]** <br>



<br><br>

**Question 7**<br>
Process is a combination of program code and a distinct set of associated data. There are a lot unique and specific trait or elements that characterized data. x is a special
program that switches the processor from one process to another.<br>

(a) Define what is x. **[1 mark]** <br>

**x is a Dispatcher**

<br>

(b) For all processes, there are **TWO (2)** main model that explains the states of processes. Name both models accordingly. **[2 marks]** <br>

   1. **TWO-STATE PROCESS MODEL**
   2. **FIVE-STATE PROCESS MODEL**

<br>

(c) Process termination stops and halts processes from executing properly. Provide **THREE (3)** reasons that leads to process termination. **[3 marks]** <br>

   1. **Normal completion**
   2. **Arithmetic error**
   3. **Parent termination**

<br>

(d) Label the following Five-State Process Model accordingly. Figure 4 **[5 marks]** <br>

![Untitled329_20240128021651](https://github.com/Tallyobin/Searchlight-Division/assets/156051265/9d36705c-91cb-4df2-8e68-d87dade3b0cc)

<br><br>

**Question 8**<br>

(a) Input / output (I/O) buffering possesses two main problems; user may hung up waiting for completion of I/O process, and the buffer itself may interfere with operating system swapping decision. In order to fix this, there are **THREE (3)** types of I/O buffering could be attempted by operating system. Name all of them. **[3 marks]** <br>

   1. **Single Buffer**
   2. **Double Buffer**
   3. **Circular Buffer**

<br>

(b) There are several disk scheduling algorithms that could be used to ensure performance of the disk I/O is optimized. Some of the common ones are FIFO, SSTF and SCAN.<br>
Given the following information, draw the reading movement of the Head on the disk, by using the C-Scan algorithm.<br>

Head initial position: Track 100<br>
Disc Track Request: 56, 58, 39, 18, 89, 159, 38, 185<br>
Head movement: Decreasing<br>

Use the following graph as your reference, plot the tracks traverse accordingly. **[9 marks]** <br>

y-axis = Track number<br>

bottom of y-axis = 199<br>
top of y-axis = 0<br>

x-axis = Time

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

# **Quiz 2 - HTML & CSS**

![image](https://github.com/Tallyobin/White-Mourning/assets/156051265/74e0bc20-2c97-4202-8d61-897d5346066b)

1. Propose suitable complete file name for the codes in Figure 1.

   ```
     a. reminder,html
     b. reminder.css
   = c. reminder.html
     d. mid-term reminder
   ```

<br>

2. What type/style of CSS is applied in line 21?.

   ```
     a. color
     b. internal
     c. css
   = d. inline
   ```

<br>

3. What type of font will be displayed if the browser does not supports all the font-family written in line 8?
   ```
     a. default serif font
   = b. default browser font
     c. default san serif font
     d. Mistral font
   ```

<br>

4. Add internal CSS codes to set the background color for the page to color ‘#FBFE8A’.

   ```
     a. body {background-colour: #FBFE8A; }
     b. body {background-color: #FBFE8A; }
   = c. body {style=background-color:#FBFE8A; }
     d. body {bg-colour: #FBFE8A;}`
   ```

<br>
   
5. Modify codes at line 20 to include css from line 6 – 9. Re-write the entire codes

   ```
     a. <p class=”p.cantik” >Mid-Term Exam for Sem 1, 23/24</p>
     b. <p style=”cantik” >Mid-Term Exam for Sem 1, 23/24</p>
   = c. <p class=”cantik” >Mid-Term Exam for Sem 1, 23/24</p>
     d. <p style=”class:cantik” >Mid-Term Exam for Sem 1, 23/24</p>
   ```

<br>

6. What will be the css codes should be written from line 10 – 13 to cater for html codes at line 19.  The text will be emphasized in green color.

   ```
     a.
     p#lawa { 
   
     font-style: italic;
   
     color: green;
   
     }

   
     b.
     p#lawa { 
   
     font-style: emp;
   
     color: green;
   
     }

   
   = c.
     #lawa {
   
     font-style: italic;
   
     color: green;
   
     }
   

     d.
     #lawa { 
   
     font-style: emp;
   
     color: green;
   
     }
     ```

<br>

7. What is the output of above codes after applying all the changes in line 19 and 20 and the internal css codes.

   ```
   = c.
     Reminder for(green color font) CMPD203/164 (purple color font) – bold + italic style
   
     Mid-Term Exam for Sem 1, 23/24 – bold style, Papyrus
   
     22 Nov 2023, 8 – 10 pm @ BV2 – bold style, red color font
   
    
   
     *ALL text is center aligned with Background color #FBFE8A


   
     b.
     Reminder for CMPD203/164 (green color font + bold style) –italic style
   
     Mid-Term Exam for Sem 1, 23/24 – bold style, Papyrus font
   
     22 Nov 2023, 8 – 10 pm @ BV2 – bold style, red color font
   
    
   
     *ALL text is center aligned with Background color #FBFE8A


   
     c.
     Reminder for(green color font) CMPD203/164 (purple color font + bold) – italic style
   
     Mid-Term Exam for Sem 1, 23/24 – bold style, Papyrus font
     
     22 Nov 2023, 8 – 10 pm @ BV2 – red color font
   
    
   
     *ALL text is center aligned with Background color #FBFE8A


   
     d.
     Reminder for(green color font) CMPD203/164 (purple color font + bold) –italic style
   
     Mid-Term Exam for Sem 1, 23/24 – bold style, Papyrus font
     
     22 Nov 2023, 8 – 10 pm @ BV2 – bold style, red color font
        
         
        
     *ALL text is aligned with Background color yellow
   ```

<br><br>

# **Quiz 3 - HTML FORM & Basic PHP**

![image (2)](https://github.com/Tallyobin/White-Mourning/assets/156051265/d68e440d-043d-4659-8d4a-7e499b05b11e)

![image (3)](https://github.com/Tallyobin/White-Mourning/assets/156051265/e4864bc9-893a-4092-abad-412fd7ca88c7)

![image (4)](https://github.com/Tallyobin/White-Mourning/assets/156051265/dd0935ca-e7b7-44f0-99b6-7b85c2169359)

1. (a)________________

   ```
   = A. "registerMe.php"
     B. registerMe.php
     C. = "registerMe.php"
     D. = registerMe.php
   ```

<br>

2. (b)_________________

   ```
   = A. method="POST"
     B. method=POST
     C. method="GET"
     D. method=GET
   ```
 
<br>

3. (c)_________________

   ```
     A. type = "username"
   = B. type = "text"
     C. type = "string"
     D. type = "varchar"
   ```
 
<br>

4. (d)_______________

   ```
     A. require
     B. selected
     C. checked
   = D. required
   ```
 
<br>

5. (e)_____________

   ```
     A. type = "pasword"
   = B. type = "password"
     C. type = "pass"
   ```
 
<br>

6. (f)_____________

   ```
     A. type = "checked"
     B. type = "checkbox"
   = C. type = "radio"
     D. type = "gender"
   ```
 
<br>

7. (g)_____________

   ```
     A. values = "male" 
     B. value = "gurl"
     C. value = " "
   = D. value = "male"
   ```
 
<br>

8. (h)______________

   ```
   = A. name = "jantina"
     B. name = "gender"
     C. name = jantina
     D. name = "female"
   ```
 
<br>

9. (i)________________

   ```
     A. Jantina
     B. Gender
   = C. Female
     D. checked
   ```
 
<br>

10. (j)____________

    ```
      A. value = "Submit"
      B. name = "Register Me"
    = C. value= "Register Me"
      D. name = "Submit"
    ```
 
<br>

11. (k)_____________

    ```
      A. <php
      B. <? php
      C. ?php
    = D. <?php
    ```
 
<br>

12. (l)____________

    ```
      A. $POST_['user'];
      B. $_POST['user']
    = C. $_POST['user'];
      D. $_POST['username'];
    ```
 
<br>

13. (m)______________

    ```
      A. $POST_['pass'];
      B. $_POST['pwd'];
    = C. $_POST['pass'];
      D. $_POST['password'];
    ```
 
<br>

14. (n)_______________

    ```
      A. $_POST['gender'];
    = B. $_POST['jantina'];
      C. $POST_['jantina'];
      D. $POST_['gender'];
    ```
 
<br>

15. (o)_____________

    ```
    = A. My DETAILS
      B. My DETAIL
      C. MY DETAILS
      D. <b> My DETAILS </b>
    ```
 
<br>

16. (p)_____________

    ```
      A. size = 50%
      B. border = "0"
    = C. border = "1"
      D. border = border
    ```
 
<br>

17. (q)______________

    ```
    = A. style = "background-color:orange;"
      B. style = "background-color:#orange;"
      C. style = "background-color:orange"
      D. style = "bground-color:orange;"
    ```
 
<br>

18. (r)_______________

    ```
      A. <?php echo $user; ?>
      B. <?php echo $username ?>
      C. <?  php echo $user; ?>
    = D. <?php echo $username; ?>
    ```
 
<br>

19. (s)_____________

    ```
      A. <?php echo $password ?>
      B. <?php echo $pass; ?>
      C. <?php echo $pass ?>
    = D. <?php echo $password; ?>
    ```

<br>

20. (t)_____________

    ```
    = A. <?php echo $gender; ?>
      B. <?php echo $gender ?>
      C. <?php echo $jantina; ?>
      D. <?php echo $jantina ?>
    ```

<br><br>

# **Quiz 4 - PHP with SQL**

1. With SQL query, how do you display data of column named "weight" from a table named "BMI"?

   ```
   = A. EXTRACT weight FROM BMI
     B. SELECT * FROM BMI
     C. SELECT BMI FROM weight
     D. SELECT weight FROM BMI
   ```

<br>

2. Which statement describe task SQL query below perform?
   
   UPDATE cuisine SET course = ‘dessert’ WHERE type= ‘pastry’;
   
   ```
     A. Add two data to the “cuisine” table.
   = B. Replace data course with dessert.
     C. Replace data course with pastry.
     D. Replace data type with pastry.
   ```

<br>

3. With SQL query, how do you delete data from a table named "MEALS" with Primary Key column “MealID” value “m100”?

   ```
     A. DELETE MealID = ‘m100’ FROM MEALS;
     B. DELETE FROM MEALS IF MealID = ‘m100’;
   = C. DELETE FROM MEALS WHERE MealID = ‘m100’;
     D. DELETE data MealID = ‘m100’ FROM MEALS;
   ```

<br>

Answer the following questions based on both Figure 1 and Figure 2 given below.

```
1 <html>
2 <body>
3 <form name="myForm" method="post" action="Enrol.php" >
4 User ID: <input type="text" name="RegID" maxlength="7"> <br>
5 Course Enrolled :
6 <select name="choose" >
7    <option value="P"> Photography  </option>
8    <option value="A"> Animation </option>
9    <option value="L"> Acting </option>
10 </select><br><br>
11 <input type="submit" value="Save">
12 </form>
13 </body>
14 </html>
```
Figure 1
<br><br>
Analyze and complete the codes below to generate a PHP file that register user’s ID with the course that they enrolled into a database.  Use the above codes as the form that user used to insert an input. 
<br><br>
(a)   Assuming that you already have the MySQL database named “MySystDb” and the table name is “MYCOURSE”. The fields in the MYCOURSE table are UserID and Course.
<br><br>
(b)   Display appropriate message if query statement is successful and display error message if query statement cannot be executed.
<br><br>
(c)   The query should be assigned to array variable RegQuery.
<br><br>
(d)   Upon successfully inserted the details, display a message “Success!”
<br><br>

```
<?php   
//retrieve form data
(a)    ______  //(2 marks)
(b)    ______  //(2 marks)
 
$pass = “”;
$log = “root”;
(c) _____ // (1 mark)
$server = “localhost”; 
 
//initialize database connection
(d) ______ //(2 marks)
 
//check database connection OK or not
(e) ______ //(1 mark)
 
       die( (f) “______” . $conn->connect_error);  //(1 mark) 
   }
else { 
 
//query to insert record
(g) ______ //(2 marks)
 
// execute query & check if query ok
(h) ______ //(2 marks)
 
     //display success message with green color text
     (i) ______ //(2 marks)
 
 }else {
 
     //display error message with orange color text
     (j)______ //(2 marks) 
 
}  
$conn->close();
?>
```

<br>

1. (a) _________________

   ```
   = A. $MyID = $_POST[“RegID”];
     B. $RegID = $_POST[“UserID”];
     C. $MyID = $_POST[UserID];
     D. $RegID = $_POST[RegID];
   ```

<br>

2. (b)______________

   ```
     A. $MyCourse = $_POST[“course”];
     B. $choose = $POST[“course”];
   = C. $MyCourse = $_POST[“choose”];
     D. $choose = $POST[“choose”];
   ```

<br>

3. (c) ______________

   ```
     A. $database = “MySQL”;
     B. $database = “MYCOURSE”;
     C. $db = “MYCOURSE”;
   = D. $db = “MySystDb”;
   ```

<br>

4. (d) _____________

   ```
     A. $link = new mysqli($server, $log, $pass, $db);
     B. $link = new mysqli($log, $pass, $db, $server);
     C. $conn = new mysqli($log, $pass, $db, $server);
   = D. $conn = new mysqli($server, $log, $pass, $db);
   ```

<br>

5. (e) _____________

   ```
   = A. if ($conn->connect_error) {
     B. if ($link->connect_error) {
     C. if ($conn->connect_error)
     D. if ($link->connect_error)
   ```

<br>

6. (f) ____________

   ```
   = A. Could not connect.
     B. “Unable to established DB connect :”
     C. Database Error,
     D. ‘Connection Problem’+
   ```

<br>

7. (g) _____________

   ```
     A. $QueryInsert = "INSERT INTO MYCOURSE values (‘”.$RegID.”’, ‘”.$choose.”’)”;
     B. $QueryInsert = "INSERT INTO MYCOURSE values (‘”.$MyID.”’, ‘”.$MyCourse.”’)”;
     C. $RegQuery = "INSERT INTO MYCOURSE values (‘”.$RegID.”’, ‘”.$choose.”’)”;
   = D. $RegQuery = "INSERT INTO MYCOURSE values (‘”.$MyID.”’, ‘”.$MyCourse.”’)”;
   ```

<br>

8. (h)_____________

   ```
     A. if ($link->query($QueryInsert) == TRUE) {
     B. if ($conn->query($QueryInsert) === TRUE) {
     C. if ($link->query($RegQuery) === TRUE) {
   = D. if ($conn->query($RegQuery) === TRUE) {
   ```

<br>

9. (i) _____________

   ```
   = A. echo "<p style='color:green;'>Success!</p>";
     B. echo "<p style='color:blue;'>Success!</p>";
     C. echo "<p style='color:green;'>Success Insert!</p>";
     D. echo "<p style='color:blue;'>Success Insert!</p>";
   ```

<br>

10. (j) ____________

    ```
      A. echo "<p style='color:red;'>Error: Invalid query ". $conn->error. "</p>";
    = B. echo "<p style='color:orange;'>Error: Invalid query ". $conn->error. "</p>";
      C. echo "<p style='color:orange;'>Error: Invalid query ". $link->error. "</p>";
      D. echo "<p style='color:red;'>Error: Invalid query ". $link->error. "</p>";
    ```

<br><br>

(i) The possible host domain name for the website could be "asoa.sg" or "arissaschoolofarts.sg."

(ii) A possible database for the website could be MySQL.

(iii) A possible web server for the website could be Apache.

(iv) A possible editor for the website development could be Visual Studio Code.

(v) A possible programming language for the website could be PHP.

<br><br>

(i) Organization: Japan Airlines, Japan
   Location: jal
   URL address: www.jal.co.jp

(ii) Organization: Ministry of Higher Education, Malaysia
    Location: mohe
    URL address: www.mohe.gov.my

<br><br>

(a) The PHP function to be called to start the session is `session_start();`.

(b) The PHP code that indicates the function to check if the session exists or not is `isset($_SESSION["whoLogIn"])`.

(c) The session variable in the codes above is `whoLogIn`.

(d) If the session variable does not exist, the output will be "No session detected. Please log in again."

(e) Codes to free and destroy the session variable in the above codes:
```php
session_unset(); // This function frees all session variables.
session_destroy(); // This function destroys the session.
```

<br><br>

(a) Set the font color for `<h1>` to green by using inline style:
```html
<h1 style="color: green;">All about Apples!</h1>
```

(b) Modify codes at line 22 to add/apply CSS style from line 6 until 9. Then, set the background page to color pink using inline style:
```html
<body style="background-color: pink;">
```

(c) Modify codes at line 32 to add/apply CSS style from line 16 until 19:
```html
<h2 style="font-size: 120%; color: white;">Type of apples:</h2>
```

(d) Name the CSS style that you wrote in question (c): The CSS style is named "special."

<br><br>

Sure, here are the modifications and additions to your HTML, CSS, and JavaScript code to meet the given requirements:

```html
<!DOCTYPE html>
<html>

<head>
    <title>#YourNickname</title>
    <style>
        body {
            background-color: pink;
            color: white; /* Added for better readability */
        }

        b {
            color: blue;
        }

        i {
            color: red;
        }
    </style>

    <script>
        function TDate() {
            var UserDate = document.getElementById("vDate").value;
            var ToDate = new Date();

            if (new Date(UserDate).getTime() > ToDate.getTime()) {
                alert("The Date must be SMALLER or Equal to today date");
                return false;
            }

            return true;
        }
    </script>
</head>

<body>

    <b>Enter video details:</b>
    <br>

    <form name="VideoForm" method="POST" onsubmit="return TDate()">

        <table>
            <tr>
                <td>Video Title: </td>
                <td><input type="text" size="50" maxlength="50" required></td>
            </tr>
            <tr>
                <td>Video Type: </td>
                <td>
                    <select required>
                        <option>- Please Choose -</option>
                        <option value="Song">Song</option>
                        <option value="Movie">Movie</option>
                        <option value="Drama">Drama</option>
                        <option value="Clips">Video Clips</option>
                    </select>
                </td>
            </tr>

            <tr>
                <td>Video Genre: </td>
                <td>
                    <input type="radio" name="vGenre" value="informative" required> Informative
                    <input type="radio" name="vGenre" value="funny"> Funny
                    <input type="radio" name="vGenre" value="romantic"> Romantic
                    <input type="radio" name="vGenre" value="horror"> Horror
                    <input type="radio" name="vGenre" value="others"> Others
                </td>
            </tr>

            <tr>
                <td>Video URL: </td>
                <td><input type="url" size="50" required></td>
            </tr>

            <tr>
                <td>Video Duration(minutes): </td>
                <td><input type="number" step="0.01" min="0.01" required></td>
            </tr>

            <tr>
                <td>Release Date: </td>
                <td><input type="date" name="vDate" max="<?php echo date('Y-m-d'); ?>" required></td>
            </tr>

        </table>

        <p><i>* ALL fields are required</i></p>
        <input type="submit" value="Save Data">
        <input type="reset">

    </form>

</body>

</html>
```

Make sure to replace `#YourNickname` with your actual nickname.

<br><br>

To achieve the requirements outlined in Figure 5, you can modify your `save_IntoDB.php` file as follows:

```php
<?php
// (a) Connect to the database
$servername = "localhost";
$username = "root";
$password = "ilovephp";
$dbname = "finalexamdb";

$conn = new mysqli($servername, $username, $password, $dbname);

// (g) Include the error notification if the database connection could not be established
if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}

// Retrieve video details from the form
$videoTitle = $_POST['videoTitle'];
$videoType = $_POST['videoType'];
$videoGenre = $_POST['videoGenre'];
$videoURL = $_POST['videoURL'];
$videoDuration = $_POST['videoDuration'];
$videoDate = $_POST['videoDate'];

// Insert data into the VIDEOLIST table
$sql = "INSERT INTO VIDEOLIST (VName, VType, VGenre, VUrl, VDuration, VDate) VALUES ('$videoTitle', '$videoType', '$videoGenre', '$videoURL', '$videoDuration', '$videoDate')";

// (h) Display error message if there is any error on the query or SQL statement could not be executed in red color
if ($conn->query($sql) === TRUE) {
    echo "<p style='color: blue;'>Video data has been saved</p>";
} else {
    echo "<p style='color: red;'>Error: " . $sql . "<br>" . $conn->error . "</p>";
}

$conn->close();
?>

<!-- (c) Video title needs to be displayed in blue color -->
<h1 style='color: blue;'>Video Details</h1>

<!-- Display the video details -->
<p><strong>Title:</strong> <?php echo $videoTitle; ?></p>
<p><strong>Type:</strong> <?php echo $videoType; ?></p>
<p><strong>Genre:</strong> <?php echo $videoGenre; ?></p>

<!-- (e) Video URL can be clickable and open-up in a new tab -->
<p><strong>URL:</strong> <a href='<?php echo $videoURL; ?>' target='_blank'><?php echo $videoURL; ?></a></p>

<!-- Displaying video duration with 'minutes' at the end -->
<p><strong>Duration:</strong> <?php echo $videoDuration; ?> minutes</p>

<!-- Displaying the date -->
<p><strong>Date:</strong> <?php echo $videoDate; ?></p>

<!-- (f) When 'here' word is clicked, it will navigate to file video form.html again -->
<p>Click <a href='video_form.html'>here</a> to go back to the video form.</p>
```

Make sure to replace the form field names (e.g., `$_POST['videoTitle']`) with the actual names used in your HTML form.

<br><br>

Here's the completed code for Figure 6 based on the provided information:

```html
<!DOCTYPE html>
<html>

<head>
    <title>#StudentID Video Hub</title>
</head>

<?php
// (i) Declare DB connection variables
$servername = "localhost";
$username = "root";
$password = "ilovephp";
$dbname = "finalexamdb";

// (ii) Create connection
$conn = new mysqli($servername, $username, $password, $dbname);

// (iii) Check connection
if ($conn->connect_error) {
    // (iv) If DB connection IS NOT OK
    die("Connection failed: " . $conn->connect_error);
} else {
    // (v) Connection OK
    // (vi) Query to select data
    $sql = "SELECT * FROM VIDEOLIST ORDER BY Vid DESC LIMIT 1";
    // (vii) Execute query
    $result = $conn->query($sql);
    if ($result->num_rows > 0) {
        // (viii) Fetch data
        $row = $result->fetch_assoc();
        $videoTitle = $row["VName"];
        $videoType = $row["VType"];
        $videoGenre = $row["VGenre"];
        $videoURL = $row["VUrl"];
        $videoDuration = $row["VDuration"];
        $videoDate = $row["VDate"];
    } else {
        // (ix) Display error message if no data found
        echo "<p style='color: red;'>No video data found.</p>";
    }
    $conn->close();
}
?>

<body>

    <h2>Display Video Data</h2>
    <br>

    <table border="1">
        <tr>
            <td>Video Title: </td>
            <td><b style="color: blue;"><?php echo $videoTitle; ?></b></td>
        </tr>
        <tr>
            <td>Video Type: </td>
            <td><b><?php echo $videoType; ?></b></td>
        </tr>
        <tr>
            <td>Video Genre: </td>
            <td><b><?php echo $videoGenre; ?></b></td>
        </tr>
        <tr>
            <td>Video URL: </td>
            <td><b><a href='<?php echo $videoURL; ?>' target='_blank'><?php echo $videoURL; ?></a></b></td>
        </tr>
        <tr>
            <td>Video Duration: </td>
            <td><b><?php echo $videoDuration; ?> minutes</b></td>
        </tr>
        <tr>
            <td>Release Date: </td>
            <td><b><?php echo $videoDate; ?></b></td>
        </tr>
    </table>
    <br>

    <?php
    // (x) Declare DB connection variables
    $servername = "localhost";
    $username = "root";
    $password = "ilovephp";
    $dbname = "finalexamdb";

    // (xi) Create connection
    $conn = new mysqli($servername, $username, $password, $dbname);

    // (xii) Check connection
    if ($conn->connect_error) {
        // (xiii) If DB connection IS NOT OK
        die("Connection failed: " . $conn->connect_error);
    } else {
        // (xiv) Connection OK
        // (xv) Query to insert data
        $sql_insert = "INSERT INTO VIDEOLIST (VName, VType, VGenre, VUrl, VDuration, VDate)
        VALUES ('Sample Video', 'Sample Type', 'Sample Genre', 'http://sampleurl.com', '5.30', '2024-01-24')";

        // (xvi) Execute query to insert data
        if ($conn->query($sql_insert) === TRUE) {
            // (xvii) Upon successfully inserted the video details
            echo "<p style='color: blue;'>Video data has been saved</p>";
        } else {
            // (xviii) Display error message if there is any error on the query or SQL statement could not be executed
            echo "<p style='color: red;'>Error: " . $sql_insert . "<br>" . $conn->error . "</p>";
        }
    }
    $conn->close();
    ?>

    <br><br>
    Click <a href='video_form.html'>here</a> to insert data
</body>

</html>
```

Make sure to replace the sample values with the actual values you want to display or insert into the database.

<br><br>

(a) The components of a Host Domain Name in a URL include:

1. Protocol
2. Subdomain (optional)
3. Domain name
4. Top-level domain (TLD)

Example: http://www.example.com

(b) PHP-related questions:

(i) By default, where should we save all files written with PHP codes? (write the complete path of the directory)

The default directory to save PHP files is the "htdocs" directory within the web server's root directory.

Complete path: For example, if you are using XAMPP, the path might be something like "C:\xampp\htdocs\"

(ii) Assuming that you save a file named index.php in the directory mentioned in question (b) (i), how would you view the page using a browser. Provide the full URL.

Full URL: http://localhost/index.php

(c) Can we view a PHP file in a browser without starting the web server? Justify your answer.

No, we cannot view a PHP file in a browser without starting the web server. PHP is a server-side scripting language, and its code needs to be processed by a web server that supports PHP before it can be rendered in a browser. Without a web server, the PHP code will not be executed, and only the raw code may be displayed in the browser.

(d) Write a line of PHP function code that creates a session variable based on the variable Login Id.

```php
$_SESSION['LoginId'] = $loginId;
```

(e) What is the PHP function code that checks if a session exists or not?

```php
if (isset($_SESSION['LoginId'])) {
    // Session exists
}
```

<br><br>

(a) Modify line 15 to include background color:

```html
<p class="iscolor" style="color: green; background-color: #66347f;">Wonderwoman</p>
```

(b) The output of the codes in Figure 1, with the modification in question (a), would be:

- The heading "MY SUPER HERO" (line 7) will have yellow color and italic style due to the class "isColor."
- The first paragraph "Superman" (line 9) will have bold, blue color, and Tahoma or Sans Serif font.
- The second paragraph "Batman" (line 11) will have red color.
- The third paragraph "Wonderwoman" (line 15) will have green color and a background color of #66347f.
- The fourth paragraph "Hulk" (line 18) will have bold, blue color, and Tahoma or Sans Serif font, similar to the first paragraph.

Note: There is a typo in the HTML; the correct class name should be "isColor" instead of "iscolor." Also, there is a duplicate id "myStyle" used for different paragraphs, which may lead to unexpected behavior. In HTML, ids should be unique within the document.

<br><br>

Here is the completed code for insertFood.php:

```php
<?php
$foodName = $_POST['foodName'];
$foodPrice = $_POST['foodPrice'];
$category = $_POST['foodCategory'];
$host = "localhost";
$user = "root";
$pass = "woy";
$db = "YummyFoodDB";

$link = new mysqli($host, $user, $pass, $db);

if ($link->connect_error) {
    die("Connection problem: " . $link->connect_error);
} else {
    $sql = "INSERT INTO FOODLIST (Food_Name, Food_Price, Food_Category) VALUES ('$foodName', '$foodPrice', '$category')";

    if ($link->query($sql) === TRUE) {
        echo "Data has been inserted into the database";
    } else {
        echo "Invalid Query: " . $link->error;
    }
}

$link->close();
?>
```

Explanation:

(a) `$category` is assigned the value of `$_POST['foodCategory']`.
(b) `$user` is assigned the value "root."
(c) `$db` is assigned the value "YummyFoodDB."
(d) `$pass` is assigned the value "woy."
(e) `$host` is assigned the value "localhost."
(f) `$link` is created using the mysqli constructor with the connection parameters.
(h) Checks if the connection is successful, and if not, it dies and prints an error message.
(k) The SQL query is constructed to insert data into the FOODLIST table.
(o) The query is executed using `$link->query($sql)`.
(p) If the query is successful, a success message is echoed.
(r) If there is an error in the query, an error message is echoed.
(t) Closes the database connection using `$link->close()`.

<br><br>

Here is the completed code for Figure 4:

```html
<!DOCTYPE html>
<html>

<body>

<img src="fn.png" width="200" height="100"> <br>
<h3>Please INSERT A FOOD DETAILS :</h3>

<br>

<form action="insertFood.php" method="POST" onsubmit="return confirmInsert()">

    Food Name
    <input type="text" name="foodName" required>

    <br>

    Food Price
    <input type="number" step="0.01" min="0.01" name="foodPrice" required>

    <br>

    Food Category :
    <select name="foodCategory" required>
        <option value="Dessert">Dessert</option>
        <option value="Appetizer">Appetizer</option>
    </select>

    <br>

    <input type="submit" value="Insert Food" onclick="return confirmInsert()">

</form>

<script>
    function confirmInsert() {
        return confirm("Are you sure to insert this record?");
    }
</script>

</body>

</html>
```

Explanation:

(a) The `img` tag is used to display the image "fn.png" with a width of 200 pixels and a height of 100 pixels.
(b) The heading "Please INSERT A FOOD DETAILS :" is included within an `h3` tag.
(c) Line break `<br>` is added for better spacing.
(d) The `form` tag is set to submit data to "insertFood.php" using the POST method and calls the `confirmInsert()` function on submission.
(e) `onsubmit` attribute is set to call the JavaScript function `confirmInsert()` to confirm whether the user wants to insert the record or not.
(f) Input field for Food Name with the `required` attribute.
(g) Input field for Food Price with the `type="number"` attribute, allowing decimal values with two floating points. `step="0.01"` ensures increments of 0.01, and `min="0.01"` ensures that the minimum value is 0.01.
(h) Line break `<br>` for better spacing.
(j) Drop-down menu for Food Category using the `select` and `option` tags.
(k) The first option "Dessert."
(l) The second option "Appetizer."
(m) Closing `option` tag.
(n) Line break `<br>` for better spacing.
(o) Submit button for inserting food.
(p) The `onclick` attribute is set to call the JavaScript function `confirmInsert()` to confirm whether the user wants to insert the record or not.
(q) The closing `</form>` tag.

The JavaScript function `confirmInsert()` uses the `confirm()` method to show a pop-up window for user confirmation. If the user clicks "OK," the form is submitted; otherwise, the form submission is canceled.

<br><br>

Here is the completed code for Figure 5:

```php
// DB connection is OK
// update data into DB
$sql = "UPDATE FOODLIST SET Food_Price = '23.99', Food_Category = 'desert' WHERE Food_Id = 300";

// Execute SQL query and check if SQL query is OK
if ($link->query($sql) === TRUE) {
    echo "<p style='color: green;'>Record has been updated</p>";
} else {
    echo "<p style='color: red;'>Error updating record: " . $link->error . "</p>";
}
```

Explanation:

(a) The SQL query is an UPDATE statement.
(b) The table name is FOODLIST.
(c) The column to be updated is Food_Price.
(d) The new value for Food_Price is '23.99'.
(e) The column to be updated is Food_Category.
(f) The new value for Food_Category is 'desert'.
(g) `$link->query($sql)` executes the SQL query.
(h) The SQL query is assigned to the `$sql` variable.
(i) If the SQL query is successful, a success message "Record has been updated" is echoed in green color.
(k) If there is an error in the query, an error message "Error updating record: " with the specific SQL error is echoed in red color.

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

## **E-commerce Final Exam**

**Section A**
  ```
  1. Which of the following is the correct abbreviation CMS?
     = Content Management System

  2. In the email campaign, __________ delivers the advertisements into the group of targeted customers.
     = Direct email marketing
  
  3. In what ways can you beat your customer's expectations?
     = By providing unique services to your customer

  4. The main advantage of online advertisement is __________.?
     = All of the above (Low-cost promotional strategy, Online advertising is promotional as well as informational, Trackable)
  
  5. Which of the following is the correct depiction of Digital Marketing?
     = All of the above (E-mail Marketing, Social Media Marketing, Web Marketing)
  ```

<br>

- The meaning of copyright, pattern, advertising, market price, customer service, affiliate marketing strategy, brand development, and paging <br>
  
  • Copyright <br>
    `Copyright refers to the legal protection granted to the creators of original works, such as literature, music, art, or software. It provides the creator with exclusive rights to use, reproduce, and distribute their work.`
  
  • Pattern <br>
    `A pattern refer to trends or recurring behaviors observed in consumer activities, website usage, or market trends. Analyzing patterns helps businesses make informed decisions.`
  
  • Advertising <br>
    `Advertising involves the promotion of products or services to a target audience. In the digital realm, it includes various online channels such as social media, search engines, display ads, and email marketing.`
  
  • Market Price <br>
    `Market price is the current price at which a product or service is traded in the market. In e-commerce, it reflects the equilibrium between supply and demand and influences pricing strategies.`
  
  • Customer Service <br>
    `Customer service involves providing support and assistance to customers before, during, and after a purchase. It aims to enhance customer satisfaction and loyalty.`
  
  • Affiliate Marketing Strategy <br>
    `Affiliate marketing is a performance-based marketing strategy where businesses reward affiliates (partners) for driving traffic or sales to the business through the affiliate's marketing efforts.`
  
  • Brand Development <br>
    `Brand development involves creating and enhancing a brand's identity, values, and image. In the digital marketing context, it includes strategies to establish a strong online presence and connect with the target audience.`
  
  • Paging <br>
    `Paging refer to the organization and presentation of content, especially in the context of websites. It involves breaking content into separate pages for better navigation and user experience.`
  
<br>

- Meaning of B2B and B2G.

  ```
  Business-to-Business (B2B)
  • e-procurement
    • Transactions conducted between Web businesses
  • Supply management (procurement)
    departments
    • Negotiate purchase transactions with suppliers

  Business-to-government (B2G)
  • Business transactions with government agencies
    • Paying taxes, filing required reports
  • B2G transactions included in B2B discussions
  ```

<br>

**Section B**

<br>

**Question 1**
- 2 basic functionality for sales in e-commerce.

  | **Functionality**                                                 | **Description** |
  | :--- | :--- |
  | Processing of HTTP requests                                       | Receive and respond to client requests for HTML pages |
  | Security services (Secure Sockets Layer)/Transport Layer Security | Verify username and password; process certificates and private/public key information required for credit card processing and other secure information |
  | File Transfer Protocol                                            | Permits transfer of very large files from server to server |
  | Search engine                                                     | Indexing of site content; keyword search capability |
  | Data capture                                                      | Log file of all visits, time, duration, and referral source |
  | E-mail                                                            | Ability to send, receive, and store e-mail messages |
  | Site management tools                                             | Calculate and display key site statistics, such as unique visitors, page requests, and origin of requests; check links on pages |

<br>

- Differences between viral marketing & lead generation marketing.

  ```
  • Viral marketing
    • Marketing designed to inspire customers to pass message to others

  • Lead generation marketing
    • Services and tools for collecting, managing, and converting leads
  ```

<br>

- Three key points of vulnerability in e-commerce environment

  ```
  • Client
  • Server
  • Communications pipeline (Internet communications channels)
  ```

  <br>

- Pharming. (attack such as malicious code)

  **Pharming**<br>
  `Automatically redirecting a URL to a different address, to benefit the hacker`

  <br>

  **Malicious Code**

  **Malvertising (malicious advertising)** : `is the use of online, malicious advertisements to spread malware and compromise systems.`

  <br>

  • **Drive-by downloads** : `A drive-by download refers to the unintentional download of malicious code onto a computer or mobile device that exposes users to different types of threats.`

  Drive-by downloads : How they works?<br>
  • A cybercriminal lures internet users with compromised websites, links, or ads.<br>
  • You click on or visit infectious material.<br>
  • Malware installs onto computer or mobile device.<br>
  • Tour system and network is potentially compromised.

  Authorized drive-by download protection tip<br>
  • Download free anti-virus software from legitimate sources and providers

  <br>

  **Ransomware** : `a going cyber attack/ malware designed to deny a user or organization access to files on their computer.`

  <br>

  Other Malicious Codes
  ```
  1. Viruses
  2. Worms
  3. Trojan Horses
  ```

<br>

**Question 2**
- The process of web analytic.

  ```
  1. Setting Business Goals
  2. Collecting Data
  3. Processing Data
  4. Reporting Data
  5. Developing an online strategy
  6. Experimenting
  ```

<br>

- Explain 3 Important factors in successful e-commerce site design.

  | **Factor**                  | **Description**                                                                     |
  | :--- | :--- |
  | Functionality               | Pages that work, load quickly, and point the customer toward your product offerings |
  | Informational               | Links that customers can easily find to discover more about you and your products   |
  | Ease of use                 | Simple foolproof navigation                                                         |
  | Redundant navigation        | Alternative navigation to the same content                                          |
  | Ease of purchase            | One or two clicks to purchase                                                       |
  | Multi-browser functionality | Site works with the most popular browsers                                           |
  | Simple graphics             | Avoids distracting, obnoxious graphics and sounds that the user cannot control      |
  | Legible text                | Avoids backgrounds that distort text or make it illegible                           |

<br>

**Question 3**
   
   - Provide a platform for effective media marketing:<br>
     `Social media platforms, such as Facebook, Instagram, Twitter, and LinkedIn.`
   
   <br>
   
   - Explain:<br>
     `Social media platforms serve as virtual spaces where businesses can share content, build brand awareness, and connect with their target audience. Through features like targeted advertising, businesses can reach specific demographics, track engagement, and receive immediate feedback.`
   
   <br>
   
   - How to illustrate GUI.<br>
     `With html & xml.`
   
   <br>
   
   - Five stages in consumer decision process in the online purchasing decision.
   
     ```
     • Awareness of need
     • Search for more information
     • Evaluation of alternatives
     • Actual purchase decision
     • Post-purchase contact with firm
     ```
   
   <br>
   
**Question 4**<br>
  Find the investment.

  An average of cost-per-click (CPC) for digital marketing investment is RM3. How many clicks can Madam Low receive if she is investing RM900.
  ```
  Total Investment = Number of clicks x CPC
  Number of Clicks = Total Investment / CPC
                 = RM900 / RM3
                   = 300
  ```
  
  <br>
  
  Given Click Through Rate (CTR) of 1.8% with 60,000 of impressions. How much will the advertiser need to spend if the CPC is RM2?
  ```
  STEP 1
   CTR = (Clicks / Impressions) x 100%
  1.8% = 1.8 x 60,000 / 100
       = 1080
  
  STEP 2
  Total Investment = Number of clicks x cost-per-click
  
  = 1080 x RM2
  = RM2160
  ```

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

## Section A ##
  
  ```
  1. Which of the following is NOT a product?
     (a) Dell personal computer
     (b) veterinarian's treatment of a pet's injuries
   = (c) business profit
     (d) lawyer's advice in a divorce case
  
  2. Below are the types of e-commerce EXCEPT
     (a) B2B
     (b) B2C
     (c) B2G
   = (d) B2H
  
  3. __________ mainly deals in buying and selling, especially on a large scale.
     (a) Shopping
     (b) Retailing
     (c) Distribution
   = (d) Commerce
  
  4. Which of the following products is suitable for e-commerce?
     (a) Fishes
     (b) Apples
   = (c) Books
     (d) Desserts
  
  5. A combination of software and information designed to provide security and information for payment is called a(n) __________.
   = (a) digital wallet
     (b) pop up ad
     (c) shopping cart
     (d) encryption
  ```

<br>

## Section B ##

**Question 1 (17m)**

**(A) Rate the importance of processing business knowledge. Justify your answer.**

Processing business knowledge is critically important for several reasons. Firstly, it enables informed decision-making, allowing businesses to respond effectively to market changes, customer preferences, and competitive landscapes. Secondly, it facilitates strategic planning by providing insights into industry trends and potential opportunities. Additionally, processing business knowledge is essential for risk management, helping businesses anticipate challenges and plan for contingencies. Overall, the ability to effectively process business knowledge is a key driver of organizational success and resilience.

<br>

**(B) Calculate yearly sales, how to calculate profit (Must know the formula, it's in the slides), know how to calculate profit and yearly profit (yearly profits times yearly sales).**

Yearly Sales can be calculated by multiplying the number of units sold by the price per unit. Profit is calculated by subtracting the total costs (including both fixed and variable costs) from the total revenue.

Formula for Profit: Profit = Total Revenue - Total Costs

Yearly Profit is calculated by multiplying the profit per unit by the total number of units sold in a year.

Formula for Yearly Profit: Yearly Profit = Profit per Unit * Total Units Sold in a Year

<br>

**(C) Differentiate eCommerce and conventional business.**

E-commerce (electronic commerce) refers to the buying and selling of goods and services over the internet, while conventional business involves physical transactions in brick-and-mortar establishments. In e-commerce, transactions occur online through websites or electronic platforms, whereas conventional business relies on face-to-face interactions in physical stores or locations.

<br>

**(D) Which eCommerce platform is the most profitable and impactful during Covid19 pandemic.**

The profitability and impact of e-commerce platforms during the Covid-19 pandemic can vary based on factors such as industry, target audience, and geographical location. Popular e-commerce platforms like Amazon, Shopify, and Alibaba experienced increased demand during the pandemic due to a surge in online shopping. However, the specific platform's profitability would depend on the strategies employed, adaptability, and the nature of the products or services offered.

<br>

**(E) Is online games considered as a eCommerce platform, Explain. (4m)**

Online games are not typically considered traditional e-commerce platforms. While they involve digital transactions and may include elements of virtual goods or in-game purchases, the primary purpose of online games is entertainment rather than facilitating the exchange of tangible goods or services. E-commerce platforms are usually associated with the buying and selling of products or services, whereas online games primarily involve the purchase of virtual items within the gaming environment. While there are financial transactions involved, the nature and purpose of these transactions differentiate online games from traditional e-commerce platforms.

<br>

**Question 2 (13m)**

**(A) Identify the two most important factor shaping decision to purchase online.**

The two most important factors shaping the decision to purchase online are Utility and Trust. Utility refers to the perceived value or usefulness of a product or service, while Trust involves the confidence and reliability customers have in the online platform or seller.

<br>

**(B) Kindly provide two basic types of wireless access (Chapter 3).**

Two basic types of wireless access are:

1. **Telephone-based wireless access:** This includes technologies like cellular networks, which enable wireless communication through mobile phones.

2. **Computer network-based wireless access:** This involves wireless communication through computer networks, such as Wi-Fi, which allows devices to connect to the internet without physical cables.

<br>

**(C) What is the feature that we need to design in our system for displaying all product. (2m)**

The feature needed to display all products in a system is a "Product Catalog" or "Product Listing." This feature organizes and presents all available products in a systematic manner, allowing users to browse, search, and view detailed information about each product.

<br>

**(D) What are the 2 main components for system design in system development life cycle.**

The two main components for system design in the system development life cycle are:

1. **Architectural Design:** This involves defining the overall structure and organization of the system, including hardware, software, databases, and how components interact.

2. **Detailed Design:** This focuses on the detailed specifications of each system component, addressing functionalities, algorithms, data structures, and interfaces.

<br>

**(E) What does AR technology stands for? Kindly provide a scenario on the AR technology adaptation in the supermarket (In the slides).**

AR stands for Augmented Reality. In a supermarket scenario, AR technology can be adapted to enhance the shopping experience. For example, customers could use AR-equipped smartphones to scan product shelves, and the AR system could provide additional information about each product, such as nutritional facts, pricing, and customer reviews, overlaid onto the real-world view through the smartphone screen. This interactive and information-rich experience can influence purchasing decisions and make the shopping process more engaging for consumers.

<br><br>

```
Advantages of E-Commerce

• Benefits extend to general society welfare
  • Products and services available in remote areas
  • Provides faster transmission
  • Lower costs to issue and secure:
    • Welfare support
    • Electronic payments of tax refunds
    • Public retirement
  • Provides fraud, theft loss protection
    • Electronic payments easier to audit and monitor
  • Reduces commuter-caused traffic, pollution
    • Due to telecommuting
```

<br>

```
Perfect (or pure) competition
there are many buyers and sellers of a product, and no single buyer or seller is powerful enough to affect the price of that product

Monopolistic Competition
there are many buyers along with a relatively larger number of sellers

Oligopoly
there are few sellers. Each seller has considerable control over price. The market actions of one seller can have a strong effect on competitors
```

<br>

```
Business-to-Consumer (B2C)
Business-to-Business (B2B)
Consumer-to-Consumer (C2C)
Business-to-government (B2G)
```

<br>

```
M-Commerce stands for Mobile Commerce.
```

<br>

```
What is E-commerce?
• Use of Internet to transact business
  • Includes Web, mobile browsers and apps
• More formally:
  • Digitally enabled commercial transactions between and among organizations and individuals
```

<br>

```
• enables informed decision-making, allowing businesses to respond effectively to market changes, customer preferences, and competitive landscapes
• facilitates strategic planning by providing insights into industry trends and potential opportunities
• essential for risk management, helping businesses anticipate challenges and plan for contingencies
```

<br>

```
Formula for Profit: Profit = Total Revenue - Total Costs
Formula for Yearly Profit: Yearly Profit = Profit per Unit * Total Units Sold in a Year
```

<br>

```
Telephone-based (mobile phones, smartphones)
Computer network-based (wireless local area network-based)
```
