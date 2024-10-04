---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
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
        url: uploads/venugopal_cv_2024_aug-public.pdf
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
        - Foundations of FinTech (Undergraduate, Masters, & Ph.D.): University of Central Florida, 2019-
        - Debt & Money Markets: University of Central Florida, 2020, 2022, 2024
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
          <li><a href="uploads/004_open-banking.pdf">Open Banking</a></li>
          <li><a href="uploads/alternative_data.pdf">Alternative Data</a></li>
          <li><a href="uploads/ev_defi_nov_2023.pdf">Decentralized Finance @UCF Dean's Speaker Series</a></li>
        </ul>
    design:      
      columns: 1
  - block: markdown
    id: media
    content:
      title: Media
      subtitle: Expert Panels, Lectures, & Media Interviews
      text: |-
        - Fireside Chat on Digital Assets, 2024 FinTech Summit <a href="https://business.ucf.edu/fintech-summit/">[UCF]</a>
        - Speaker, Blockchain and DeFi, 2024  FinTech Summit <a href="https://business.ucf.edu/fintech-summit/">[UCF]</a>
        - Effect of pollution on businesses, CNBC TV18, December 2023
        - The (Potential) Benefits & Risks of Decentralized Finance}, 2023 Dean's Speaker Series <a href="https://eshwarvenugopal.weebly.com/teaching.html">[UCF]</a>
        - Government Infusions and Financial Stability, Moderator <a href="https://sciences.ucf.edu/news/india-center-webinar-financial-stability/">[India Center]</a>
        - Rattled crypto industry could emerge stronger after USDC Depeg <a href="https://cointelegraph.com/news/rattled-crypto-industry-could-emerge-stronger-after-usdc-depeg">[Cointelegraph]</a>
        - Stablecoins: good as the buck, or breaking the buck? <a href="https://www.risk.net/investing/risk-management/7955944/stablecoins-good-as-the-buck-or-breaking-the-buck">[Risk.net]</a>
        - Stability of Stablecoins and FTX Collapse <a href="https://cointelegraph.com/news/how-stable-are-stablecoins-in-the-ftx-crypto-market-contagion">[Cointelegraph]</a>
        - 2022 Federal Housing Finance Agency's Econ Summit, Panelist <a href="https://www.fhfa.gov/Media/Documents/FHFA-Econ-Summit-Agenda-Fall-2022.pdf">[FHFA]</a>
        - Speaker, FinTech & Blockchain Session, 2022 UCF Annual Accounting Conference <a href="https://business.ucf.edu/wp-content/uploads/sites/4/2022/05/Final_0505_2022-UCF-Accounting-Conference-Schedule_Rm_Assigns.pdf">[UCF]</a>
        - Moderator, FinTech Digital Transformation Panel, 2022 UCF FinTech Summit <a href="https://business.ucf.edu/fintech-summit-2022/">[UCF]</a>
        - Panelist, Fintech and Blockchain, 2022 <a href="https://www.cecs.ucf.edu/utvs/2022-presenters/">[UTVS]</a>
        - Cryptocurrencies: A non-technical primer, 2021 UCF Foundation 
        - Uganda’s gold discovery: What it could mean for crypto <a href="https://cointelegraph.com/news/uganda-s-gold-discovery-what-it-could-mean-for-crypto">[Cointelegraph]</a>
        - Crypto’s crash shows digital currency is not a hedge against inflation <a href="https://qz.com/2116509/crypto-isnt-a-safe-haven-during-high-inflation/">[Quartz]</a>
        - Stablecoins aren’t stable: Why TerraUSD is crashing <a href="https://qz.com/2165213/stablecoins-arent-stable-why-terra-is-crashing/">[Quartz]</a>
        - How high can meme coin prices go? <a href="https://qz.com/2080561/how-high-can-dogecoin-and-shiba-inu-coin-go/">[Quartz]</a>
        - Are NFTs Really a Thing? <a href="https://business.ucf.edu/are-nfts-really-a-thing/">[Podcast]</a>
        - On security while investing in Cryptocurrencies <a href="https://www.mynews13.com/fl/orlando/news/2021/04/24/consumers-are-on-their-own-in-the-world-of-cryptocurrency#">[News 13]</a>
        - Speaker & Panelist, Blockchain Task force in Tallahassee <a href="https://eshwarvenugopal.weebly.com/uploads/5/9/1/6/59166679/ucf-blockchain-taskforce-dec2019-v4_macro.pdf">[Presentation]</a> <a href="https://thefloridachannel.org/videos/12-13-19-florida-blockchain-task-force/">[Video]</a>
        - Panelist, 2018 Data Science Summit: Smart Cities of the Future
        - Moderator: India - Growth, Challenge, and Opportunity Series:  
    design:      
      columns: 1
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
