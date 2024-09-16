---
layout: home
description: "An unofficial collection of information about a data breach suffered by the City of Columbus in summer 2024"
date: 2024-08-13
---

<section class="grid-container usa-section">
<div class="grid-row grid-gap">

<div class="display-none tablet:display-block tablet:grid-col-4 ">
  <div class="position-sticky top-3">
    <p class="margin-top-3">
      <a class="usa-button usa-button--secondary width-full" href="https://www.columbus.gov/Services/Cybersecurity">Visit Columbus.gov<br/> for more information</a>
    </p>
    <nav aria-label="In-page navigation">
      <ul class="usa-sidenav">
        <li><a href="#you">Your info may have been ...</a></li>
        <li><a href="#what">What you can do</a></li>
        <li><a href="#stolen">What was stolen</a></li>
        <li><a href="#notstolen">What wasn't stolen</a></li>
        <li><a href="#help">Help this site</a></li>
        <li><a href="#sources">Sources</a></li>
      </ul>
    </nav>
  </div>
</div><!-- grid-col -->

<div class="tablet:grid-col-8 usa-prose" markdown=1>

<div
  class="usa-summary-box"
  role="region"
  aria-labelledby="summary-box-key-information"
>
  <div class="usa-summary-box__body">
    <h2 class="usa-summary-box__heading" id="you">
      Your personal information may have been copied if:
    </h2>
    <div class="usa-summary-box__text">
      <ul class="usa-list">
<li markdown=1>
you are a juvenile or adult victim of a crime[^1] or fire[^7]
</li>
<li markdown=1>
you are an overt or undercover police officer[^1]
</li>
<li markdown=1>
you are a confidential police informant[^1]
</li>
<li markdown=1>
you ever filed a report with Columbus Police[^6]
</li>
<li markdown=1>
your driver's license or state ID was ever scanned at a City facility[^1]
</li>
<li markdown=1>
you are an employee of the City of Columbus[^1]
</li>
<li markdown=1>
you have provided the City with your Social Security Number[^1]
</li>
      </ul>
      <p>This list is based on press reports and filings in lawsuits concerning the hack.</p>
    </div>
  </div>
</div>

## My data may have been stolen. What can I do? {#what}

<iframe class="width-full" style="aspect-ratio: 16/9;" src="https://www.youtube-nocookie.com/embed/3d1_lIZADGg" title="YouTube video player" frameborder="0" allow="encrypted-media" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

The City of Columbus offers free credit reporting via Experian to adults and minors with Social Security Numbers, and sole-proprietor businesses operating under an SSN instead of an EIN.[^9]

<a class="usa-button usa-button--secondary" href="https://www.columbus.gov/Services/Cybersecurity">Visit Columbus.gov for more information</a>

## How can I check if my data was included in the leak?

The hacking group which copied the data, Rhysida, says that they stole approximately 6.5 terabytes of data, of which they have released about 45 percent on their dark web site. Rhysida's website is accessible to anyone with a TOR web browser.[^2] 

> “It doesn’t take any sophistication or vast technical knowledge to access that,” [[Electronic Frontier Foundation](https://eff.org) Free Speech and Transparency Litigation Director Aaron Mackey] said. “You can actually use a Google search to download a browser called Tor, which stands for ‘the onion router,’ and it allows you to actually access a lot of this material online. So it’s as sophisticated as downloading an app on your phone.” [^10]

## What was stolen? {#stolen}

Based on press reports, court documents, news comments, and City staff comments, the following data was stolen:

- backups of City employee computers including folders, documents, downloads, and favorites,[^3] their computer's [Windows registry](https://en.wikipedia.org/wiki/Windows_Registry)[^3], and other files saved on their computers[^6]
- backups of City databases[^3],[^5]
- personal information of City employees and former employees[^9] which "likely contains payroll data" [^5], including names, addresses, phone numbers, bank routing numbers and account information of City employees[^5], and the names, addresses, and phone numbers of City employee emergency contacts[^7]
- "Attendance Enterprise" data including paid time, vacation time, and badge numbers for 2,837 city employees[^7]
- data "related to watershed, AEP, and the utility companies"[^5]
- data from the City's MATRIX Prosecutor and MatrixCrime databases, including "confidential records for cases of rape, homicide, child abuse and domestic violence," as far back as 2014, with details including the scene of the crime, weapons used, evidence, victim injuries, victim statements, victim Social Security Numbers, victim addresses, victim phone numbers, and reports made by officers[^6] [^8] [^9]
- any report made by a resident to CPD[^6]
- identifying details of the Columbus Police Department's undercover officers[^6]
- Columbus Division of Fire's "Firehouse" database, including the SSNs of citizens involved in fire department investigations, and victims' names, addresses, and Vehicle Identification Numbers, from 2014 to 2023[^7]
- lists of visitors to City Hall[^8] [^9]
- lists of individuals allegedly banned from City buildings[^8]

## Was any data not stolen? {#notstolen}

Columbus' parking management provider ParkMobile confirmed that they do not share customer data "directly" with the City, and have received no reports of data loss connected to this hack.[^11]

## Help contribute to this site {#help}

[This is not an official Columbus government website]({% link about.markdown %}).

If you're aware of a fact that isn't listed here, _and that hasn't been reported in the press or in court_, please contact local law enforcement and/or the press.

If you're aware of a fact that has been reported in the press, or has been reported in court, send that publicly-posted link to Ben Keith via the usual methods. He has zero desire to receive the data itself, or to receive your original research into the data.

</div><!-- grid-col -->
</div><!-- grid-row -->
</section><!-- grid-container -->

## Sources {#sources}

[^1]: "[Columbus City Council briefed on data breach: Here's what we learned](https://www.dispatch.com/story/news/local/2024/09/10/columbus-it-chief-tells-council-23-percent-of-city-computer-systems-remain-down-from-cyberattack/75106743007/)" _The Columbus Dispatch_ Published 6:09 a.m. ET Sept. 10, 2024. Updated: 11:10 a.m. ET Sept. 10, 2024. [Archive.org copy](https://web.archive.org/web/20240911020213/https://www.dispatch.com/story/news/local/2024/09/10/columbus-it-chief-tells-council-23-percent-of-city-computer-systems-remain-down-from-cyberattack/75106743007/). "And details provided by Ross — that the hacked data contained the identities of juvenile victims, undercover police officers, confidential police informants, driver licenses, employee information, Social Security numbers and more — is just 'some,' but not all of what got stolen. The city is still evaluating the extent of the damage, Orth said."
[^2]: "[City of Columbus sues man after he discloses severity of ransomware attack](https://arstechnica.com/security/2024/08/city-of-columbus-sues-man-after-he-discloses-severity-of-ransomware-attack/)" _Ars Technica_ Published 4:00 p.m. ET August 8, 2024. [Archive.org copy](https://web.archive.org/web/20240909235639/https://arstechnica.com/security/2024/08/city-of-columbus-sues-man-after-he-discloses-severity-of-ransomware-attack/). "[...] the city of Columbus fell victim to a ransomware attack on July 18 that [siphoned 6.5 terabytes](https://www.nbc4i.com/news/local-news/columbus/ransomware-group-claims-columbus-attack-selling-6-terabytes-of-passwords-and-more/) of the city’s data. A ransomware group known as Rhysida took credit for the attack and offered to auction off the data with a starting bid of about [$1.7 million in bitcoin](https://www.nbc4i.com/news/local-news/columbus/devastating-stolen-columbus-data-leaked-by-ransomware-group-after-auction-gets-no-bids/). On August 8, after the auction failed to find a bidder, Rhysida released what it said was about 45 percent of the stolen data on the group’s dark web site, which is accessible to anyone with a TOR browser."
[^3]: Comment on the above _Ars Technica_ article by [C&eacute;dric J.1](https://arstechnica.com/security/2024/08/city-of-columbus-sues-man-after-he-discloses-severity-of-ransomware-attack/?comments=1&comments-page=5): "I just downloaded the TOR Browser, googled the Rhysida Onion address, browsed their Website to the Columbus Dump and now I have under my eyes a ton of Windows User's profiles with all their folders (documents, desktop, downloads, favorites, etc.), user's registry (NTUSER.DAT) and Gigabytes of databases backups."
[^4]: Subsequent comment on the above _Ars Technica_ article by [C&eacute;dric J.1](https://arstechnica.com/security/2024/08/city-of-columbus-sues-man-after-he-discloses-severity-of-ransomware-attack/?comments=1&comments-page=6): "Having looked at the data a bit more I can confirm that this is not the sort of thing you want on the internet and the data is easily accessible or is absolutely not corrupted in any way. So the reasearcher is 100% correct with it's statements that the official downplayed the gravity of the leak. After less than 5 minutes of browsing this is kind of data you get: [image]"
[^5]: "Ohio State professor explains what's been posted on the dark web after Columbus ransomware attack" NBC4i. Published: 6:00 PM EDT August 8, 2024. Updated: 6:00 PM EDT August 8, 2024. [Archive.org copy](https://web.archive.org/web/20240914214854/https://www.10tv.com/article/news/local/ohio-state-professor-explains-whats-been-posted-on-dark-web-after-columbus-ransomware-attack/530-a3e859de-f012-4ffd-a10b-e824bf622e89).
[^6]: "[Chief disturbed after database naming undercover Columbus officers found in leak ](https://www.nbc4i.com/news/investigates/chief-disturbed-after-database-naming-undercover-columbus-cops-found-in-leak/)" NBC4i. Posted: Aug 28, 2024, 05:44 PM EDT. Updated: Aug 28, 2024, 10:56 PM EDT. [Archive.org copy](https://web.archive.org/web/20240905094316/https://www.nbc4i.com/news/investigates/chief-disturbed-after-database-naming-undercover-columbus-cops-found-in-leak/). ""
[^7]: "[Gut-wrenching:’ More victims found in Columbus data leak](https://www.nbc4i.com/news/investigates/how-far-back-data-leak-goes-in-affecting-columbus-employees/)" NBC4i. Posted Aug 19, 2024, 05:09 PM EDT. Updated Aug 19, 2024, 05:24 PM EDT. [Archive.org copy](https://web.archive.org/web/20240827224925/https://www.nbc4i.com/news/investigates/how-far-back-data-leak-goes-in-affecting-columbus-employees/). "One of those databases, called “Attendance Enterprise,” tracked paid time, vacation and badge numbers for 2,837 city workers. Goodwolf showed the records also contained employees’ Social Security numbers, as well as the names, addresses and phone numbers for emergency contacts. This is yet another set of data that’s exploitable, according to Goodwolf."<br/>"Goodwolf also found a database called “Firehouse,” which contained Social Security numbers for citizens involved in Columbus Division of Fire investigations. It also held sensitive details in notes from hazmat and arson investigations, as well as victims’ names, addresses and vehicle identification numbers. The records stretched from 2014 to 2023, and included deceased victims."
[^8]: Motion for _ex parte_ temporary restraining order, filed August 29, 2024. Case 24 CV 006703 in [the Court of Common Please, Franklin County, Ohio, Civil Division](https://fcdcfcjs.co.franklin.oh.us/CaseInformationOnline/). "Among the data stolen from the City and presumably posted to the dark web are the two backup prosecutor and crime databases. These databases contain large amounts of data gathered by the City prosecutors and the Columbus Division of Police pertaining to misdemeanor crimes prosecuted by the City’s Attorney’s office dating back to at least 2015. his data would potentially include sensitive personal information of police officers, as well as the reports submitted by arresting and undercover officers involved in the apprehension of persons charged criminally by the City prosecutor’s office. These databases also contain the personal information of crime victims of all ages, including minors, and witnesses to the crimes the City prosecuted from at least 2015 to the present." Internal citations omitted. "[...] visitors to City Hall, victims of domestic violence and other misdemeanor offenses, and lists of individuals allegedly compiled to prevent their access to City buildings, just to name a few."
[^9]: Columbus City Council meeting, September 9, 2024. Relevant time stamps are [0:39:30](https://youtu.be/V8-4ehTsXQM?t=2189) to [1:23:30](https://youtu.be/V8-4ehTsXQM?t=5025).
[^10]: "[Columbus whistleblower lawsuit violates First Amendment, digital rights group says ](https://www.nbc4i.com/news/investigates/columbus-whistleblower-lawsuit-violates-first-amendment-digital-rights-group-says/)", NBC4i. Posted Aug 30, 2024, 06:00 PM EDT. Updated Sep 3, 2024, 04:38 PM EDT. [Archive.org copy](https://web.archive.org/web/20240913172537/https://www.nbc4i.com/news/investigates/columbus-whistleblower-lawsuit-violates-first-amendment-digital-rights-group-says/). 
[^11]: "[Columbus parking app gives answer on whether data leak impacts its users ](https://www.nbc4i.com/news/investigates/columbus-parking-app-gives-answer-on-whether-data-leak-impacts-its-users/)" NBC4i. Posted Aug 26, 2024, 06:22 PM EDT. Updated Aug 26, 2024, 06:22 PM EDT. [Archive.org copy](https://web.archive.org/web/20240830102823/https://www.nbc4i.com/news/investigates/columbus-parking-app-gives-answer-on-whether-data-leak-impacts-its-users/). “For clarity, ParkMobile powers digital parking payments in Columbus via the ParkColumbus white label mobile app and website. A white label allows cities the option to display a customized branded experience through ParkMobile,” a spokesperson wrote. “To note, no customer data from a parking transaction is shared directly with the city. We also have no information suggesting that ParkMobile customer data is involved in the cyberattack on the city of Columbus.”