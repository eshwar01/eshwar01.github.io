---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
fontsize: 12pt
type: landing

design:
  # Default section spacing
  spacing: "3rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Venugopal_CV.pdf
    design:
      columns: '1'
  - block: collection
    id: research
    content:
      title: 'Publications'
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
      count: 0    
    design:
      view: citation
      list_format: 1
      columns: 1  
  - block: collection
    content:
      title: Working Papers
      filters:
        folders:
          - workings
        featured_only: true
    design:
      view: Citation
      columns: 1

  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |-
        **Instructor:**
        - Foundations of FinTech (Undergraduate): University of Central Florida, Spring 2019- 
        - Foundations of FinTech (Masters'): University of Central Florida, Fall 2022- 
        - Ph.D Seminar on FinTech: University of Central Florida, Spring 2021, 2023 
        - Debt & Money Markets: University of Central Florida, Spring 2020, 2022, 2024 
        - Corporate Finance: University of Houston - Summer 2016 
        - Financial Management: Monash University - Fall 2011 & Spring 2012 
        
        **Teaching Assistant: University of Houston, USA**
        - Intermediate Corporate Finance: Valuation (MBA): 2013-2018 
        - Managerial Finance (MBA): 2015 - 2018
        - Game Theory (Ph.D.): 2015 - 2018
        - Investments: 2013
        - Principles of Financial Management: 2012-2013

        **Teaching Associate: Monash University, Australia​**
        - Financial Management: 2010 - 2012
        - Money and Capital Markets: 2010-2012

        **FinTech lecture notes:**
        <ul>
          <li><a href="uploads/003_Banking.pdf">Banking</a>, <a href="uploads/004_open-banking.pdf">Open Banking</a></li>
          <li>Marketplace financing: <a href="uploads/006_P2P-Lending.pdf">P2P Lending</a>, <a href="uploads/006_Crowdfunding.pdf">Crowd Financing</a></li>
          <li><a href="uploads/alternative_data.pdf">Alternative Data</a></li>
          <li>Blockchain: <a href="uploads/009_Blockchain.pdf">I</a>, <a href="uploads/010_Blockchain-extended.pdf">II</a>, <a href="uploads/011_Toy-Blockchain-Implementation.pdf">III</a></li>
          <li>Payments: <a href="uploads/013_Financial-Services-Payments.pdf">Traditional</a>, <a href="uploads/012_Cryptocurrencies & ICOs.pdf">Cryptocurrencies & ICO</a></li>
          <li>Decentralized Finance: <a href="uploads/013_DeFi.pdf">I</a>, <a href="uploads/014_DeFi-II">II</a>, <a href="uploads/ev_defi_nov_2023.pdf">Dean's Speaker Series</a></li>
        </ul>
    design:      
      columns: 1
  - block: markdown
    id: media
    content:
      title: Media
      text: |-
        #### Expert Panels, Lectures, & Media Interviews:
        - Making India an Advanced Economy by 2047: What Will It Take?, Moderator <a href="https://events.ucf.edu/event/3524624/making-india-an-advanced-economy-by-2047-what-will-it-take/">[India Center]</a>
        - Fireside Chat on Digital Assets, 2024 FinTech Summit <a href="https://business.ucf.edu/fintech-summit/">[UCF]</a>
        - Blockchain and DeFi, 2024  FinTech Summit <a href="https://business.ucf.edu/fintech-summit/">[UCF]</a>
        - Effect of pollution on businesses, CNBC TV18, December 2023
        - The (Potential) Benefits & Risks of Decentralized Finance}, 2023 Dean's Speaker Series <a href="https://eshwarvenugopal.weebly.com/teaching.html">[UCF]</a>
        - Government Infusions and Financial Stability, Moderator <a href="https://sciences.ucf.edu/news/india-center-webinar-financial-stability/">[India Center]</a>
        - Rattled crypto industry could emerge stronger after USDC Depeg <a href="https://cointelegraph.com/news/rattled-crypto-industry-could-emerge-stronger-after-usdc-depeg">[Cointelegraph]</a>
        - Stablecoins: good as the buck, or breaking the buck? <a href="https://www.risk.net/investing/risk-management/7955944/stablecoins-good-as-the-buck-or-breaking-the-buck">[Risk.net]</a>
        - Stability of Stablecoins and FTX Collapse <a href="https://cointelegraph.com/news/how-stable-are-stablecoins-in-the-ftx-crypto-market-contagion">[Cointelegraph]</a>
        - 2022 Federal Housing Finance Agency's Econ Summit <a href="https://www.fhfa.gov/Media/Documents/FHFA-Econ-Summit-Agenda-Fall-2022.pdf">[FHFA]</a>
        - FinTech & Blockchain Session, 2022 UCF Annual Accounting Conference <a href="https://business.ucf.edu/wp-content/uploads/sites/4/2022/05/Final_0505_2022-UCF-Accounting-Conference-Schedule_Rm_Assigns.pdf">[UCF]</a>
        - FinTech Digital Transformation Panel, Moderator, 2022 UCF FinTech Summit <a href="https://business.ucf.edu/fintech-summit-2022/">[UCF]</a>
        - Fintech and Blockchain, 2022 <a href="https://www.cecs.ucf.edu/utvs/2022-presenters/">[UTVS]</a>
        - Cryptocurrencies: A non-technical primer, 2021 UCF Foundation 
        - Uganda’s gold discovery: What it could mean for crypto <a href="https://cointelegraph.com/news/uganda-s-gold-discovery-what-it-could-mean-for-crypto">[Cointelegraph]</a>
        - Crypto’s crash shows digital currency is not a hedge against inflation <a href="https://qz.com/2116509/crypto-isnt-a-safe-haven-during-high-inflation/">[Quartz]</a>
        - Stablecoins aren't stable: Why TerraUSD is crashing <a href="https://qz.com/2165213/stablecoins-arent-stable-why-terra-is-crashing/">[Quartz]</a>
        - How high can meme coin prices go? <a href="https://qz.com/2080561/how-high-can-dogecoin-and-shiba-inu-coin-go/">[Quartz]</a>
        - Are NFTs Really a Thing? <a href="https://business.ucf.edu/are-nfts-really-a-thing/">[Podcast]</a>
        - On security while investing in Cryptocurrencies <a href="https://www.mynews13.com/fl/orlando/news/2021/04/24/consumers-are-on-their-own-in-the-world-of-cryptocurrency#">[News 13]</a>
        - Blockchain Task force in Tallahassee, Speaker & Panelist <a href="https://eshwarvenugopal.weebly.com/uploads/5/9/1/6/59166679/ucf-blockchain-taskforce-dec2019-v4_macro.pdf">[Presentation]</a> <a href="https://thefloridachannel.org/videos/12-13-19-florida-blockchain-task-force/">[Video]</a>
        - 2018 Data Science Summit: Smart Cities of the Future, Panelist
        - Moderator: India - Growth, Challenge, and Opportunity Series  
        
        ### FinTech @UCF:
        #### <a href="https://business.ucf.edu/degree/ms-fintech/">Master of Science in FinTech</a>
        - <a href="chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://business.ucf.edu/wp-content/uploads/sites/4/2022/03/PRINT-AGENDA-FinTech-Summit_22.pdf">​FinTech Summit 2022</a> <a href="https://www.flickr.com/photos/ucfbusiness/albums/72177720297857935/">[Photos]</a>
        - <a href="chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://business.ucf.edu/wp-content/uploads/sites/4/2024/04/FinTech-Summit-2024-Agenda_Web.pdf">FinTech Summit 2024</a> <a href="https://www.flickr.com/photos/ucfbusiness/albums/72177720316076237/">[Photos]</a>
        
        <div class="video-container">
          <iframe src="https://www.youtube.com/embed/8KquWxx1Fdg"></iframe>
        </div>

        #### FinTech @Undergraduate level
          - <a href="https://www.ucf.edu/degree/fintech-certificate-2/">Certificate</a> 
          - <a href="https://www.ucf.edu/degree/fintech-minor/">Minor</a>  

          <div class="video-container">
              <iframe src="https://www.youtube.com/embed/wnSIEQ1pydE"></iframe>
          </div>
        
        ### Moderated Discussions @India Center:
          - Do Repeated Cash Infusions Help Financial Stability? (Moderator)
            <div class="video-container">
              <iframe src="https://www.youtube.com/embed/aIMYi_ttc8A"></iframe>
            </div>    
          - Making India an Advanced Economy by 2047 (Moderator)
            <div class="video-container">
              <iframe src="https://www.youtube.com/embed/OXIfoHy-Ql8"></iframe>
            </div>    
    design:      
      columns: 1
---
