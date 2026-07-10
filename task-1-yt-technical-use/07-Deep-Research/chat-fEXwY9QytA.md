User: # Act as a research analyst.

Research the effectiveness of COVID-19 vaccines in reducing severe disease among adults in the United States.

## Research workflow:

1. Generate a concise research plan.
2. Search the web for authoritative sources.
3. Limit yourself to a maximum of 3 search results.
4. Read only the pages necessary to answer the question (maximum 3 pages).
5. Prioritize:
   - CDC
   - NIH
   - JAMA
   - NEJM
6. Ignore news articles, blogs, opinion pieces, social media, and commercial websites.
7. Stop searching once sufficient evidence has been collected.

## Deliverables:

- Executive Summary in Markdown format
- Evidence Table
    - Source
    - Publication date
    - Study type
    - Main conclusion
- Confidence Assessment
- Limitations
- References

## API Budget:

- Maximum 2 research plan.
- Maximum 4 search query.
- Maximum 6 search results.
- Maximum 6 page reads.
- Do not perform follow-up searches unless no authoritative sources are found.
- Prefer extracting only the relevant sections instead of reading entire websites.

Assistant: 

Tool: Plan updated successfully.

Assistant: 

Tool: Plan updated successfully.

Assistant: 

Tool: {"organic_results":[{"title":"Interim Estimates of 2024–2025 COVID-19 Vaccine ...","snippet":"Vaccine effectiveness (VE) of 2024–2025 COVID-19 vaccine was 33% against COVID-19–associated emergency department (ED) or urgent care (UC) visits among adults ...","source":"Centers for Disease Control and Prevention | CDC (.gov)","link":"https://www.cdc.gov/mmwr/volumes/74/wr/mm7406a1.htm"},{"title":"Vaccine Effectiveness | COVID-19","snippet":"CDC's COVID-19 vaccine effectiveness program protects public health through the data-driven science of conducting observational studies that ...","source":"Centers for Disease Control and Prevention | CDC (.gov)","link":"https://www.cdc.gov/covid/php/surveillance/vaccine-effectiveness.html"},{"title":"Effectiveness of SARS-CoV-2 mRNA Vaccines for Preventing ...","snippet":"During March–May 2021, SARS-CoV-2 mRNA vaccines were highly effective for preventing Covid-19 hospitalizations among US adults. SARS-CoV-2 vaccination was ...","source":"PubMed Central (PMC) (.gov)","link":"https://pmc.ncbi.nlm.nih.gov/articles/PMC8282104/"},{"title":"Estimated 2024-2025 COVID-19 Vaccine Effectiveness ...","snippet":"Vaccine effectiveness against COVID-19–associated hospitalization was 40% (95% CI, 27%-51%), and protection was sustained through 90 to 179 days ...","source":"JAMA","link":"https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2844612"},{"title":"Effectiveness of 2024–2025 COVID-19 Vaccines in ...","snippet":"In this analysis, receipt of a 2024–2025 COVID-19 vaccine dose provided additional protection against COVID-19–associated ED/UC visits among ...","source":"Centers for Disease Control and Prevention | CDC (.gov)","link":"https://www.cdc.gov/mmwr/volumes/74/wr/mm7440a1.htm"},{"title":"Benefits of Getting Vaccinated | Covid","snippet":"The 2023–2024 COVID-19 vaccines reduced the risk of COVID-19 hospitalization among older adults by about 50% in the first 2 months after ...","source":"Centers for Disease Control and Prevention | CDC (.gov)","link":"https://www.cdc.gov/covid/vaccines/benefits.html"},{"title":"Updated Bivalent COVID-19 Vaccines Reduce Risk of ... - PMC","snippet":"Severe disease rates among admitted patients were 13.3% unvaccinated, 11.9% vaccinated, 12.2% boosted, and 8.1% FV&BB (P = 0.052). The FV&BB group showed a 4.0% ...","source":"PubMed Central (PMC) (.gov)","link":"https://pmc.ncbi.nlm.nih.gov/articles/PMC11161184/"},{"title":"CDC Pauses Release of COVID-19 Vaccine Effectiveness ...","snippet":"CDC Pauses Release of COVID-19 Vaccine Effectiveness Study · Reduced emergency visits by 50% · Reduced hospitalizations by 55%.","source":"Infectious Disease Advisor","link":"https://www.infectiousdiseaseadvisor.com/news/cdc-pauses-release-of-covid-19-vaccine-effectiveness-study/"},{"title":"New study finds COVID-19 vaccines are highly effective in ...","snippet":"“These findings indicate that vaccination is very effective in reducing the risk of hospitalization with COVID-19 in older adults, a highly ...","source":"Vanderbilt University Medical Center |","link":"https://www.vumc.org/health-policy/covid19-vaccine-effective-study-cdc"}]}

Assistant: 

Tool: Plan updated successfully.

Assistant: 

Tool: {
  "success": true,
  "data": {
    "json": {
      "keyFindings": [
        {
          "studyDesign": "Test-negative design",
          "dates": "September 2024–January 2025",
          "population": "Adults aged ≥18 years (VISION Network)",
          "veEstimates": {
            "estimate": 33,
            "confidenceInterval": "28%–38%"
          },
          "severeOutcomesData": "COVID-19 associated emergency department (ED) or urgent care (UC) visits",
          "conclusions": "Vaccination with a 2024–2025 COVID-19 vaccine dose provides additional protection against COVID-19–associated ED/UC encounters compared with no vaccination.",
          "publicationDate": "February 27, 2025",
          "authors": "Ruth Link-Gelles, et al."
        },
        {
          "studyDesign": "Test-negative design",
          "dates": "September 2024–January 2025",
          "population": "Immunocompetent adults aged ≥65 years (VISION Network)",
          "veEstimates": {
            "estimate": 45,
            "confidenceInterval": "36%–53%"
          },
          "severeOutcomesData": "COVID-19 associated hospitalizations",
          "conclusions": "Vaccination with a 2024–2025 COVID-19 vaccine dose provides significant protection against hospitalizations compared with no vaccination.",
          "publicationDate": "February 27, 2025",
          "authors": "Ruth Link-Gelles, et al."
        },
        {
          "studyDesign": "Test-negative design",
          "dates": "September 2024–January 2025",
          "population": "Immunocompromised adults aged ≥65 years (VISION Network)",
          "veEstimates": {
            "estimate": 40,
            "confidenceInterval": "21%–54%"
          },
          "severeOutcomesData": "COVID-19 associated hospitalizations",
          "conclusions": "Vaccination with a 2024–2025 COVID-19 vaccine dose provides significant protection against hospitalizations compared with no vaccination, although less than immunocompetent adults.",
          "publicationDate": "February 27, 2025",
          "authors": "Ruth Link-Gelles, et al."
        },
        {
          "studyDesign": "Test-negative design",
          "dates": "September 2024–January 2025",
          "population": "Immunocompetent adults aged ≥65 years (IVY Network)",
          "veEstimates": {
            "estimate": 46,
            "confidenceInterval": "26%–60%"
          },
          "severeOutcomesData": "COVID-19 associated hospitalizations",
          "conclusions": "Vaccination with a 2024–2025 COVID-19 vaccine provides substantial protection against hospitalizations among immunocompetent adults aged ≥65 years.",
          "publicationDate": "February 27, 2025",
          "authors": "Ruth Link-Gelles, et al."
        }
      ]
    },
    "metadata": {
      "citation_author": [
        "Ruth Link-Gelles, PhD",
        "Sean Chickery, DHSc",
        "Alexander Webber, MPH",
        "Toan C. Ong, PhD",
        "Elizabeth A.K. Rowley, DrPH",
        "Malini B. DeSilva, MD",
        "Kristin Dascomb, MD, PhD",
        "Stephanie A. Irving, MHS",
        "Nicola P. Klein, MD, PhD",
        "Shaun J. Grannis, MD",
        "Michelle A. Barron",
        "Sarah E. Reese, PhD",
        "Charlene McEvoy, MD",
        "Tamara Sheffield, MD",
        "Allison L. Naleway, PhD",
        "Ousseny Zerbo, PhD",
        "Colin Rogerson, MD",
        "Wesley H. Self, MD",
        "Yuwei Zhu, MD",
        "Adam S. Lauring, MD, PhD",
        "Emily T. Martin, PhD",
        "Ithan D. Peltan, MD",
        "Adit A. Ginde, MD",
        "Nicholas M. Mohr, MD",
        "Kevin W. Gibbs, MD",
        "David N. Hager, MD, PhD",
        "Matthew E. Prekker, MD",
        "Amira Mohamed, MD",
        "Nicholas Johnson, MD",
        "Jay S. Steingrub, MD",
        "Akram Khan, MBBS",
        "Jamie R. Felzer, MD",
        "Abhijit Duggal, MD",
        "Jennifer G. Wilson, MD",
        "Nida Qadir, MD",
        "Christopher Mallow, MD",
        "Jennie H. Kwon, DO",
        "Cristie Columbus, MD",
        "Ivana A. Vaughn, PhD",
        "Basmah Safdar, MD",
        "Jarrod M. Mosier, MD",
        "Estelle S. Harris, MD",
        "James D. Chappell, MD, PhD",
        "Natasha Halasa, MD",
        "Cassandra Johnson, MS",
        "Karthik Natarajan, PhD",
        "Nathaniel M. Lewis, PhD",
        "Sascha Ellington, PhD",
        "Emily L. Reeves, MPH",
        "Jennifer DeCuir, MD, PhD",
        "Meredith McMorrow, MD",
        "Clinton R. Paden, PhD",
        "Amanda B. Payne, PhD",
        "Fatimah S. Dawood, MD",
        "Diya Surie, MD",
        "CDC COVID-19 Vaccine Effectiveness Collaborators"
      ],
      "citation_volume": "74",
      "cdc:page_origin": "wcms",
      "cdc:page_type": "cdc_mmwr",
      "og:description": "This report describes 2024–2025 COVID-19 vaccine effectiveness against COVID-19-associated emergency department or urgent care encounters.",
      "cdc:content_source": "DEPUTY DIRECTOR FOR PUBLIC HEALTH SCIENCE AND SURVEILLANCE",
      "cdc:maintained_by": "DEPUTY DIRECTOR FOR PUBLIC HEALTH SCIENCE AND SURVEILLANCE",
      "twitter:card": "summary_large_image",
      "og:image:type": "image/png",
      "title": "Interim Estimates of 2024–2025 COVID-19 Vaccine Effectiveness Among Adults Aged ≥18 Years — VISION and IVY Networks, September 2024–January 2025  | MMWR",
      "cdc:version": "4.25.12",
      "citation_title": "Interim Estimates of 2024–2025 COVID-19 Vaccine Effectiveness Among Adults Aged ≥18 Years — VISION and IVY Networks, September 2024–January 2025",
      "og:author": "CDC",
      "og:title": "Interim Estimates of 2024–2025 COVID-19 ...",
      "twitter:creator": "@CDCgov",
      "theme-color": [
        "#075290",
        "#0056b3"
      ],
      "article:author": "CDCMMWR",
      "citation_issn": "0149-21951545-861X",
      "ogUrl": "https://www.cdc.gov/mmwr/volumes/74/wr/mm7406a1.htm",
      "robots": "index, archive",
      "viewport": "width=device-width, initial-scale=1, shrink-to-fit=no",
      "citation_categories": "Full Report",
      "citation_publication_date": "2025",
      "og:type": "article",
      "ogImage": "https://www.cdc.gov/mmwr/volumes/74/wr/social-media/mm7406a1_COVIDVEAdults_IMAGE_27Feb2025_1200x675_v2.png?_=10175",
      "twitter:title": "Interim Estimates of 2024–2025 COVID-19 ...",
      "cdc:build": "5475",
      "twitter:description": "This report describes 2024–2025 COVID-19 vaccine effectiveness against COVID-19-associated emergency department or urgent care encounters.",
      "msapplication-TileColor": "#0056b3",
      "fb:app_id": "205691699516606",
      "DC.date": "2026-02-05T12:05:09Z",
      "description": "This report describes 2024–2025 COVID-19 vaccine effectiveness against COVID-19-associated emergency department or urgent care encounters. ",
      "cdc:last_published": "2026-02-05T12:05:43Z",
      "ogTitle": "Interim Estimates of 2024–2025 COVID-19 ...",
      "twitter:image:src": "https://www.cdc.gov/mmwr/volumes/74/wr/social-media/mm7406a1_COVIDVEAdults_IMAGE_27Feb2025_1200x675_v2.png?_=10175",
      "cdc:first_published": "February 27, 2025",
      "cdc:template_version": [
        "4.5",
        "4.0"
      ],
      "mobile-web-app-capable": "yes",
      "apple-mobile-web-app-capable": "yes",
      "twitter:site": "@CDCMMWR",
      "publishedTime": "2025-11-17",
      "cdc:content_id": "115667",
      "cdc:wcms_build": "4.25.12 - b.5475",
      "cdc:last_reviewed": "November 17, 2025",
      "Description": "This report describes 2024–2025 COVID-19 vaccine effectiveness against COVID-19-associated emergency department or urgent care encounters. ",
      "citation_journal_title": "MMWR. Morbidity and Mortality Weekly Report",
      "article:published_time": "2025-11-17",
      "cdc:last_updated": "November 17, 2025, 01:00 PM",
      "ogSiteName": "Centers for Disease Control and Prevention",
      "og:image": "https://www.cdc.gov/mmwr/volumes/74/wr/social-media/mm7406a1_COVIDVEAdults_IMAGE_27Feb2025_1200x675_v2.png?_=10175",
      "language": "en-us",
      "citation_journal_abbrev": "MMWR Morb Mortal Wkly Rep",
      "cdc:tp_version": "4.26.6",
      "ogDescription": "This report describes 2024–2025 COVID-19 vaccine effectiveness against COVID-19-associated emergency department or urgent care encounters.",
      "og:url": "https://www.cdc.gov/mmwr/volumes/74/wr/mm7406a1.htm",
      "citation_doi": "10.15585/mmwr.mm7406a1",
      "twitter:domain": "https://www.cdc.gov/mmwr/volumes/74/wr/mm7406a1.htm?s_cid=mm7406a1_w",
      "og:site_name": "Centers for Disease Control and Prevention",
      "favicon": "https://www.cdc.gov/TemplatePackage/4.0/assets/imgs/favicon/favicon-32x32.png",
      "scrapeId": "019f4a8f-e7b1-773d-a0c5-67d8291c2727",
      "sourceURL": "https://www.cdc.gov/mmwr/volumes/74/wr/mm7406a1.htm",
      "url": "https://www.cdc.gov/mmwr/volumes/74/wr/mm7406a1.htm",
      "statusCode": 200,
      "contentType": "text/html",
      "proxyUsed": "basic",
      "cacheState": "hit",
      "cachedAt": "2026-07-10T05:42:17.822Z",
      "creditsUsed": 5,
      "concurrencyLimited": false
    }
  }
}

Assistant: 

Tool: {
  "success": true,
  "data": {
    "json": {
      "study_type": "Multicenter, test-negative, case-control study",
      "dates": "September 1, 2024 - April 30, 2025",
      "population": {
        "group": "Adults aged 18 years or older, hospitalized in the US."
      },
      "VE_estimates": {
        "effectiveness": 40,
        "confidence_intervals": "27%-51%"
      },
      "main_conclusions": "The 2024-2025 COVID-19 vaccines provided 40% effectiveness against hospitalization and 79% against invasive mechanical ventilation or death, demonstrating notable protection against severe disease during the 2024-2025 season.",
      "publication_date": "February 3, 2026"
    },
    "metadata": {
      "citation_abstract": "<h3>Importance</h3><p>As SARS-CoV-2 JN.1 lineage descendants continue to evolve, evaluating COVID-19 vaccine effectiveness (VE) against severe COVID-19 remains important to guide vaccination strategies.</p><h3>Objective</h3><p>To estimate the VE of the 2024-2025 COVID-19 vaccines against COVID-19–associated hospitalization and severe in-hospital outcomes overall and by time since dose (7-89, 90-179, and ≥180 days), JN.1 descendant lineage (KP.3.1.1, XEC, LP.8.1), and spike protein mutations associated with immune evasion.</p><h3>Design, Setting, and Participants</h3><p>This multicenter, test-negative, case-control study conducted by the Investigating Respiratory Viruses in the Acutely Ill Network included adult patients (aged ≥18 years) hospitalized between September 1, 2024, and April 30, 2025, at 26 hospitals in 20 US states. Case patients presented with COVID-19–like illness and positive SARS-CoV-2 nucleic acid or antigen test results; control patients had COVID-19–like illness but tested negative for SARS-CoV-2.</p><h3>Exposure</h3><p>Receipt of a 2024-2025 COVID-19 vaccine at least 7 days before illness onset.</p><h3>Main Outcomes and Measures</h3><p>Main outcomes were COVID-19–associated hospitalization and severe in-hospital outcomes (supplemental oxygen therapy, acute respiratory failure, intensive care unit admission, and invasive mechanical ventilation or death). Logistic regression was used to estimate the odds of vaccination in case and control patients, adjusting for demographics, clinical characteristics, and enrollment region. The VE was estimated as (1 – adjusted odds ratio) × 100%.</p><h3>Results</h3><p>A total of 8493 patients (median [IQR] age, 66 [54-76] years; 4338 female [51.1%]), including 1888 case patients with COVID-19 (among whom 951 [50.4%] had successful whole-genome sequencing, including 348 [36.6%] with KP.3.1.1, 218 [22.9%] with XEC, and 134 [14.1%] with LP.8.1 infections) and 6605 control patients were enrolled. Vaccine effectiveness against COVID-19–associated hospitalization was 40% (95% CI, 27%-51%), and protection was sustained through 90 to 179 days after vaccination. Vaccine effectiveness was higher against the most severe outcome of invasive mechanical ventilation or death at 79% (95% CI, 55%-92%). It was 49% (95% CI, 25%-67%) against hospitalization with KP.3.1.1, 34% (95% CI, 4%-56%) against XEC, and 24% (95% CI, −19% to 53%) against LP.8.1, with increasing median time since dose receipt among vaccinated case patients due to sequential circulation patterns (60, 89, and 141 days, respectively). The VE was similar against lineages with spike protein S31 deletion (41% [95% CI, 22%-56%]) and T22N and F59S substitutions (37% [95% CI, 9%-57%]).</p><h3>Conclusions and Relevance</h3><p>In this multicenter, case-control analysis of VE, 2024-2025 COVID-19 vaccines may have provided protection against hospitalizations and severe in-hospital outcomes as multiple JN.1 descendant lineages circulated. Monitoring COVID-19 VE, including stratifying by SARS-CoV-2 lineage and spike protein mutations, remains important to guide COVID-19 vaccine composition and recommendations.</p>",
      "title": "Estimated Effectiveness of 2024-2025 COVID-19 Vaccination Against Severe COVID-19 | Infectious Diseases | JAMA Network Open | JAMA Network",
      "citation_journal_abbrev": "JAMA Netw Open",
      "language": "en",
      "ogUrl": "https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2844612",
      "og:image": [
        "https://cdn.jamanetwork.com/ama/content_public/journal/jamanetworkopen/939778/zoi251532t1_1769460396.19957.png?Expires=2147483647&Signature=emOdhkcQzGnRCLvfjHQDCQyC5Pfxrz5srfaEbJ~LfUQquCgC6QkzpIcqHuX1-xypdbOh9j8PUq40QojsTniYrMZCr1zhDL40JOdN9U~Fc-zywpgSRCoe3E6Vdh3Bx8T7GFGYYcm4XQlYjL7B0xxlXBY-D-A3kOoU2i5WmKb388KyAF~C1-qxu8RuOiJ7Ck3gtZAd5J5DWax~hEmTbFaPwGX~MIEXa2WyjCo6wAh4wlGHzoOMBOJ9fLGPRRyqzaMlr-eaM-9~wdNt7OqBpFQtwiiKmBkOz77WmxMatNn5NV1YQezxftScFjKqzX60M0fe4ARWCGhdLvJlS3jYBR5OQA__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA",
        "https://cdn.jamanetwork.com/ama/content_public/journal/jamanetworkopen/939778/zoi251532f1_1769460396.20957.png?Expires=2147483647&Signature=KbhLmwMN0mA2iod7D7R7v~hK25T~lfpFXBb8zX2uNsZ35wsTKmh6v~ootQE3kU2MutQDiW3ft4qShUOvLJReehvtTNY9wOHsInAjXPNUXdYC7g3il8PNHog1mXg32Uaie7XkzfxWj1yl4W5gAyq~pNfUlacZ-dh-zaQv9c578FCcmyb7ozFktIxt6FagBQNRAecYB2SGlSuAbyTktCFtyqhd7Qq3nThvmQrQ8dMw~nNQgXAR~cns9p7svsmW0oPQwqZXZAoQAo9A~Lv3Zi6JXgPP4zH-dbpuucdonJVZvHMIBt~fQCal3M88x7ZWctzyzUejOEQrF5gwaf7tDaAtvA__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA",
        "https://cdn.jamanetwork.com/ama/content_public/journal/jamanetworkopen/939778/zoi251532f2_1769460396.21957.png?Expires=2147483647&Signature=VB8cz4jmvgPmaV3yMaBreds4MTXeisVG95KERAIWZQxsCB6IHoSYsWVBN8x-7q~d0kYLZ~Kkmw0HPZpDVIRuxzedD~jvzVJa3aJcXdVZIM1SL6~6ikGBXcTrf1Ozp4U8GNXKb-VBCRPZHHrkrI81xx9f3Bh8w0zTHf9J~~VZVkaC~e0RL1WLzSZndXgmDRVNUc9TWnZ2RraAU3PiLNJxJl~kdagVSqAQTlW7R6SdPB59lLLg0~mZaxCp57yvGGxxJICUEAPwr7NCR9Jez2wqZW6bhBESKbpwX--XkdL2k5JwqwF3Jgs8p1pAJ8amoRxGNKR7n-8QrCzXCbHveVolag__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA",
        "https://cdn.jamanetwork.com/ama/content_public/journal/jamanetworkopen/939778/zoi251532f3_1769460396.22957.png?Expires=2147483647&Signature=ZupC-QHnWvrD322oyHgNo1YO9AW9S1yt3NR2CpbH~EqWmnPE7bWxpxCE1H1ngZ8ovG0FKDeK4qeSAU5DoNC7LVvDK5EYE3RHhVL2BWJO~tn05gIgdCSfiI4N2fP5ar2VYD2OTeg~XyhuWzYyoVPJTWypmZ8S946Ki88PlEsS0isU6QmTxbqyI0W~s0ybiqTkua6ec5vehKDgbxAKRSuXiMJyqP~Caoq~OBg4bSR1NdoyvXFEW6Nty30WZABAO2vf2XmJht~NM-5FwSvotSLIey9xN4bFSQzr69~w2TKuG-pAI0xn3W8ll-bynxYVwx532uXH2voYoTwXlua6-57yHw__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA",
        "https://cdn.jamanetwork.com/ama/content_public/journal/jamanetworkopen/939778/zoi251532f4_1769460396.23957.png?Expires=2147483647&Signature=wpKUGwqaYVNai51arUnE~HPml9YjE2~xk1hJ8Qochy1s0phvlFIno81ay2lr7orhjb4wBd2Dwj4ebhholMJlfge6l1Dd6L6--oN1BpbWdLyWDtqIo7oPCIicun9mPAv1l7WQnUEbK66D~qVdqUwLETPTn2uf4fb7rLOBDsBqV8sUBOBzzymmzm3w5HKawu7feLc9QmpOm6SxtITVeP6cWci3wYuJrHwgrF9dSizCeeLNXV2a~GkGJPSNZ0evzETk3NSE6tq27dw33yUiApE5UuPvlhPVjqOcHHsUCSVZlw232lYqHfg0tWog2NPSQ7pGCdEY0n92IpVCBIpV6pgMtQ__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA"
      ],
      "format-detection": "telephone=no",
      "og:type": "Article",
      "og:url": "https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2844612",
      "citation_pmid": [
        "41632473",
        "41632473"
      ],
      "citation_title": "Estimated Effectiveness of 2024-2025 COVID-19 Vaccination Against Severe COVID-19",
      "citation_publication_date": "2026/02/02",
      "citation_journal_title": "JAMA Network Open",
      "og:description": "This case-control study estimates vaccine effectiveness of the 2024-2025 COVID-19 vaccines against severe COVID-19 and investigates whether it varied by SARS-CoV-2 lineage or spike protein mutations.",
      "citation_keyword": [
        "sars-cov-2",
        "covid-19",
        "covid-19 vaccines",
        "vaccine efficacy",
        "spike protein, human",
        "mutation",
        "mechanical ventilation"
      ],
      "citation_volume": "9",
      "citation_author_institution": [
        "Coronavirus and Other Respiratory Viruses Division, National Center for Immunization and Respiratory Diseases, Centers for Disease Control and Prevention, Atlanta, Georgia",
        "Coronavirus and Other Respiratory Viruses Division, National Center for Immunization and Respiratory Diseases, Centers for Disease Control and Prevention, Atlanta, Georgia",
        "Department of Internal Medicine, University of Michigan, Ann Arbor",
        "Department of Microbiology and Immunology, University of Michigan, Ann Arbor",
        "Department of Internal Medicine, University of Michigan, Ann Arbor",
        "Department of Microbiology and Immunology, University of Michigan, Ann Arbor",
        "Department of Internal Medicine, University of Michigan, Ann Arbor",
        "Department of Microbiology and Immunology, University of Michigan, Ann Arbor",
        "Department of Emergency Medicine, Yale University School of Medicine, New Haven, Connecticut",
        "Department of Emergency Medicine, University of Colorado School of Medicine, Aurora",
        "Department of Pulmonary/Critical Care Medicine, Intermountain Medical Center, Murray, Utah",
        "Division of Respiratory, Critical Care, and Occupational Pulmonary Medicine, Department of Medicine, University of Utah, Salt Lake City",
        "Department of Pulmonary/Critical Care Medicine, Intermountain Medical Center, Murray, Utah",
        "Division of Respiratory, Critical Care, and Occupational Pulmonary Medicine, Department of Medicine, University of Utah, Salt Lake City",
        "Baylor Scott and White Health, Temple, Texas",
        "Baylor College of Medicine, Temple, Texas",
        "Baylor Scott and White Health, Temple, Texas",
        "Baylor College of Medicine, Temple, Texas",
        "Baylor College of Medicine, Temple, Texas",
        "Texas A&M University College of Medicine, Dallas",
        "Department of Emergency Medicine, University of Iowa, Iowa City",
        "Department of Medicine, Wake Forest School of Medicine, Winston-Salem, North Carolina",
        "Department of Medicine, Johns Hopkins University School of Medicine, Baltimore, Maryland",
        "Department of Emergency Medicine, Hennepin County Medical Center, Minneapolis, Minnesota",
        "Department of Medicine, Montefiore Medical Center, Albert Einstein College of Medicine, Bronx, New York",
        "Department of Medicine, Montefiore Medical Center, Albert Einstein College of Medicine, Bronx, New York",
        "Department of Emergency Medicine, University of Washington, Seattle",
        "Division of Pulmonary, Critical Care and Sleep Medicine, University of Washington, Seattle",
        "Department of Medicine, Oregon Health and Sciences University, Portland",
        "Department of Medicine, Oregon Health and Sciences University, Portland",
        "Department of Medicine, Cleveland Clinic, Cleveland, Ohio",
        "Department of Emergency Medicine, Stanford University School of Medicine, Stanford, California",
        "Department of Medicine, University of California, Los Angeles",
        "Department of Medicine, University of California, Los Angeles",
        "Department of Medicine, University of Miami, Miami, Florida",
        "Department of Medicine, Emory University School of Medicine, Atlanta, Georgia",
        "Department of Medicine, Washington University in St Louis, St Louis, Missouri",
        "Department of Medicine, The Ohio State University, Columbus",
        "Department of Public Health Sciences, Henry Ford Health, Detroit, Michigan",
        "Division of Infectious Diseases, Henry Ford Health, Detroit, Michigan",
        "Department of Emergency Medicine, University of Arizona, Tucson",
        "Department of Epidemiology, University of Michigan, Ann Arbor",
        "Department of Medicine, University of Utah, Salt Lake City",
        "Department of Emergency Medicine, Vanderbilt University Medical Center, Nashville, Tennessee",
        "Department of Biostatistics, Vanderbilt University Medical Center, Nashville, Tennessee",
        "Vanderbilt Institute for Clinical and Translational Research, Vanderbilt University Medical Center, Nashville, Tennessee",
        "Department of Biostatistics, Vanderbilt University Medical Center, Nashville, Tennessee",
        "Influenza Division, National Center for Immunization and Respiratory Diseases, Centers for Disease Control and Prevention, Atlanta, Georgia",
        "Influenza Division, National Center for Immunization and Respiratory Diseases, Centers for Disease Control and Prevention, Atlanta, Georgia",
        "Department of Medicine, Vanderbilt University Medical Center, Nashville, Tennessee",
        "Department of Health Policy, Vanderbilt University Medical Center, Nashville, Tennessee",
        "Department of Medicine, Vanderbilt University Medical Center, Nashville, Tennessee",
        "Department of Medicine, Vanderbilt University Medical Center, Nashville, Tennessee",
        "Department of Pediatrics, Vanderbilt University Medical Center, Nashville, Tennessee",
        "Department of Pediatrics, Vanderbilt University Medical Center, Nashville, Tennessee",
        "Department of Biostatistics, Vanderbilt University Medical Center, Nashville, Tennessee",
        "Department of Emergency Medicine, Vanderbilt University Medical Center, Nashville, Tennessee",
        "Vanderbilt Institute for Clinical and Translational Research, Vanderbilt University Medical Center, Nashville, Tennessee",
        "Coronavirus and Other Respiratory Viruses Division, National Center for Immunization and Respiratory Diseases, Centers for Disease Control and Prevention, Atlanta, Georgia",
        "Coronavirus and Other Respiratory Viruses Division, National Center for Immunization and Respiratory Diseases, Centers for Disease Control and Prevention, Atlanta, Georgia",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network"
      ],
      "citation_reference": [
        "Preliminary estimates of COVID-19 burden for 2024-2025. Centers for Disease Control and Prevention. 2025. Accessed December 3, 2025. https://www.cdc.gov/covid/php/surveillance/burden-estimates.html ",
        "Staying up to date with COVID-19 vaccines. Centers for Disease Control and Prevention. 2025. Accessed June 12, 2025. https://www.cdc.gov/covid/vaccines/stay-up-to-date.html ",
        "citation_title=When to update COVID-19 vaccine composition.; citation_author=Grant  R; citation_author=Sacks  JA; citation_author=Abraham  P;  citation_journal_title=Nat Med;  citation_year=2023;  citation_volume=29;  citation_issue=4;  citation_pages=776-780; ",
        "FDA approves and authorizes updated mRNA COVID-19 vaccines to better protect against currently circulating variants. US Food and Drug Administration. August 23, 2024. Accessed June 12, 2025. https://www.fda.gov/news-events/press-announcements/fda-approves-and-authorizes-updated-mrna-covid-19-vaccines-better-protect-against-currently ",
        "Thornburg NJ. 2024-2025 Update on current epidemiology of COVID-19 and SARS-CoV-2 genomics. US Food and Drug Administration. May 2025. Accessed August 1, 2025. https://www.fda.gov/media/186593/download ",
        "citation_title=Role of glycosylation mutations at the N-terminal domain of SARS-CoV-2 XEC variant in immune evasion, cell-cell fusion, and spike stability.; citation_author=Li  P; citation_author=Faraone  JN; citation_author=Hsu  CC;  citation_journal_title=J Virol;  citation_year=2025;  citation_volume=99;  citation_issue=4; ",
        "citation_title=Enhanced immune evasion of SARS-CoV-2 variants KP.3.1.1 and XEC through N-terminal domain mutations.; citation_author=Liu  J; citation_author=Yu  Y; citation_author=Jian  F;  citation_journal_title=Lancet Infect Dis;  citation_year=2025;  citation_volume=25;  citation_issue=1;  citation_pages=e6-e7; ",
        "citation_title=Genomic surveillance for SARS-CoV-2 variants: circulation of Omicron XBB and JN.1 lineages — United States, May 2023–September 2024.; citation_author=Ma  KC; citation_author=Castro  J; citation_author=Lambrou  AS;  citation_journal_title=MMWR Morb Mortal Wkly Rep;  citation_year=2024;  citation_volume=73;  citation_issue=42;  citation_pages=938-945; ",
        "citation_title=Antibody evasiveness of SARS-CoV-2 subvariants KP.3.1.1 and XEC.; citation_author=Wang  Q; citation_author=Guo  Y; citation_author=Mellis  IA;  citation_journal_title=Cell Rep;  citation_year=2025;  citation_volume=44;  citation_issue=4; ",
        "citation_title=Structural and functional insights into the evolution of SARS-CoV-2 KP.3.1.1 spike protein.; citation_author=Feng  Z; citation_author=Huang  J; citation_author=Baboo  S;  citation_journal_title=Cell Rep;  citation_year=2025;  citation_volume=44;  citation_issue=7; ",
        "citation_title=Neutralization and spike stability of JN.1-derived LB.1, KP.2.3, KP.3, and KP.3.1.1 subvariants.; citation_author=Li  P; citation_author=Faraone  JN; citation_author=Hsu  CC;  citation_journal_title=mBio;  citation_year=2025;  citation_volume=16;  citation_issue=5; ",
        "Variants and genomic surveillance. Centers for Disease Control and Prevention. August 28, 2025. Accessed December 30, 2025. https://www.cdc.gov/covid/php/variants/variants-and-genomic-surveillance.html ",
        "citation_title=Use of COVID-19 vaccines for persons aged ≥6 months: recommendations of the Advisory Committee on Immunization Practices - United States, 2024-2025.; citation_author=Panagiotakopoulos  L; citation_author=Moulia  DL; citation_author=Godfrey  M;  citation_journal_title=MMWR Morb Mortal Wkly Rep;  citation_year=2024;  citation_volume=73;  citation_issue=37;  citation_pages=819-824; ",
        "COVID-19 vaccination coverage and intent for vaccination, adults 18 years and older, United States. Centers for Disease Control and Prevention. May 5, 2025. Accessed May 14, 2025. https://www.cdc.gov/covidvaxview/weekly-dashboard/adult-vaccination-coverage.html ",
        "citation_title=Strengthening the Reporting of Observational Studies in Epidemiology (STROBE) statement: guidelines for reporting observational studies.; citation_author=STROBE Initiative; citation_author=von Elm  E; citation_author=Altman  DG; citation_author=Egger  M; citation_author=Pocock  SJ; citation_author=Gøtzsche  PC; citation_author=Vandenbroucke  JP;  citation_journal_title=BMJ;  citation_year=2007;  citation_volume=335;  citation_issue=7624;  citation_pages=806-808; ",
        "citation_title=Effectiveness of updated 2023-2024 (monovalent XBB.1.5) COVID-19 vaccination against SARS-CoV-2 Omicron XBB and BA.2.86/JN.1 lineage hospitalization and a comparison of clinical severity-IVY network, 26 hospitals, October 18, 2023-March 9, 2024.; citation_author=Ma  KC; citation_author=Surie  D; citation_author=Lauring  AS;  citation_journal_title=Clin Infect Dis; ",
        "citation_title=Effectiveness of monovalent mRNA COVID-19 vaccination in preventing COVID-19-associated invasive mechanical ventilation and death among immunocompetent adults during the Omicron variant period - IVY Network, 19 U.S. states, February 1, 2022-January 31, 2023.; citation_author=IVY Network; citation_author=DeCuir  J; citation_author=Surie  D; citation_author=Zhu  Y;  citation_journal_title=MMWR Morb Mortal Wkly Rep;  citation_year=2023;  citation_volume=72;  citation_issue=17;  citation_pages=463-468; ",
        "citation_title=Vaccine effectiveness of primary series and booster doses against COVID-19 associated hospital admissions in the United States: living test negative design study.; citation_author=Influenza and Other Viruses in the Acutely Ill (IVY) Network; citation_author=Adams  K; citation_author=Rhoads  JP; citation_author=Surie  D;  citation_journal_title=BMJ;  citation_year=2022;  citation_volume=379; ",
        "citation_title=Early estimates of bivalent mRNA vaccine effectiveness in preventing COVID-19-associated hospitalization among immunocompetent adults aged ≥65 years - IVY Network, 18 states, September 8-November 30, 2022.; citation_author=IVY Network; citation_author=Surie  D; citation_author=DeCuir  J; citation_author=Zhu  Y;  citation_journal_title=MMWR Morb Mortal Wkly Rep;  citation_year=2022;  citation_volume=71;  citation_issue=5152;  citation_pages=1625-1630; ",
        "citation_title=Effects of confounding bias in coronavirus disease 2019 (COVID-19) and influenza vaccine effectiveness test-negative designs due to correlated influenza and COVID-19 vaccination behaviors.; citation_author=Doll  MK; citation_author=Pettigrew  SM; citation_author=Ma  J; citation_author=Verma  A;  citation_journal_title=Clin Infect Dis;  citation_year=2022;  citation_volume=75;  citation_issue=1;  citation_pages=e564-e571; ",
        "citation_title=Assessment and mitigation of bias in influenza and COVID-19 vaccine effectiveness analyses - IVY Network, September 1, 2022-March 30, 2023.; citation_author=Lewis  NM; citation_author=Harker  EJ; citation_author=Leis  A;  citation_journal_title=Vaccine;  citation_year=2025;  citation_volume=43;  citation_issue=pt 2; ",
        "citation_title=Evaluation of test-negative design estimates of influenza vaccine effectiveness in the context of multiple, co-circulating, vaccine preventable respiratory viruses.; citation_author=Leis  AM; citation_author=Wagner  A; citation_author=Flannery  B; citation_author=Chung  JR; citation_author=Monto  AS; citation_author=Martin  ET;  citation_journal_title=Vaccine;  citation_year=2024;  citation_volume=42;  citation_issue=26; ",
        "citation_title=Comparison of mRNA vaccine effectiveness against COVID-19-associated hospitalization by vaccination source: immunization information systems, electronic medical records, and self-report-IVY Network, February 1-August 31, 2022.; citation_author=Surie  D; citation_author=Bonnell  LN; citation_author=DeCuir  J;  citation_journal_title=Vaccine;  citation_year=2023;  citation_volume=41;  citation_issue=29;  citation_pages=4249-4256; ",
        "citation_title=Effectiveness of original monovalent and bivalent COVID-19 vaccines against COVID-19-associated hospitalization and severe in-hospital outcomes among adults in the United States, September 2022-August 2023.; citation_author=Investigating Respiratory Viruses in the Acutely Ill (IVY) Network; citation_author=DeCuir  J; citation_author=Surie  D; citation_author=Zhu  Y;  citation_journal_title=Influenza Other Respir Viruses;  citation_year=2024;  citation_volume=18;  citation_issue=11; ",
        "citation_title=Durability of XBB.1.5 vaccines against Omicron subvariants.; citation_author=Lin  DY; citation_author=Du  Y; citation_author=Xu  Y; citation_author=Paritala  S; citation_author=Donahue  M; citation_author=Maloney  P;  citation_journal_title=N Engl J Med;  citation_year=2024;  citation_volume=390;  citation_issue=22;  citation_pages=2124-2127; ",
        "citation_title=Estimates of bivalent mRNA vaccine durability in preventing COVID-19-associated hospitalization and critical illness among adults with and without immunocompromising conditions - VISION Network, September 2022-April 2023.; citation_author=Link-Gelles  R; citation_author=Weber  ZA; citation_author=Reese  SE;  citation_journal_title=MMWR Morb Mortal Wkly Rep;  citation_year=2023;  citation_volume=72;  citation_issue=21;  citation_pages=579-588; ",
        "citation_title=Duration of protection against mild and severe disease by COVID-19 vaccines.; citation_author=Andrews  N; citation_author=Tessier  E; citation_author=Stowe  J;  citation_journal_title=N Engl J Med;  citation_year=2022;  citation_volume=386;  citation_issue=4;  citation_pages=340-350; ",
        "citation_title=Effectiveness of COVID-19 vaccines against SARS-CoV-2 infection and severe outcomes in adults: a systematic review and meta-analysis of European studies published up to 22 January 2024.; citation_author=Zhou  G; citation_author=Dael  N; citation_author=Verweij  S;  citation_journal_title=Eur Respir Rev;  citation_year=2025;  citation_volume=34;  citation_issue=175; ",
        "citation_title=Effectiveness of mRNA vaccination in preventing COVID-19-associated invasive mechanical ventilation and death - United States, March 2021-January 2022.; citation_author=IVY Network; citation_author=Tenforde  MW; citation_author=Self  WH; citation_author=Gaglani  M;  citation_journal_title=MMWR Morb Mortal Wkly Rep;  citation_year=2022;  citation_volume=71;  citation_issue=12;  citation_pages=459-465; ",
        "citation_title=Interim estimates of 2024-2025 COVID-19 vaccine effectiveness among adults aged ≥18 years — VISION and IVY Networks, September 2024-January 2025.; citation_author=CDC COVID-19 Vaccine Effectiveness Collaborators; citation_author=Link-Gelles  R; citation_author=Chickery  S; citation_author=Webber  A;  citation_journal_title=MMWR Morb Mortal Wkly Rep;  citation_year=2025;  citation_volume=74;  citation_issue=6;  citation_pages=73-82; ",
        "citation_title=Early effectiveness of the BNT162b2 KP.2 vaccine against COVID-19 in the US Veterans Affairs Healthcare System.; citation_author=Appaneal  HJ; citation_author=Lopes  VV; citation_author=Puzniak  L;  citation_journal_title=Nat Commun;  citation_year=2025;  citation_volume=16;  citation_issue=1;  citation_pages=4033",
        "citation_title=Effectiveness of spring 2024 (XBB.1.5) and autumn 2024 (JN.1) COVID-19 vaccination against hospitalisation in England.; citation_author=Abdul Aziz  N; citation_author=Kirsebom  FCM; citation_author=Allen  A; citation_author=Andrews  N;  citation_journal_title=Vaccine;  citation_year=2025;  citation_volume=67; ",
        "citation_title=Effectiveness of the BNT162b2 and mRNA-1273 JN.1-adapted vaccines against COVID-19-associated hospitalisation and death: a Danish, nationwide, register-based, cohort study.; citation_author=Hansen  CH; citation_author=Lassaunière  R; citation_author=Rasmussen  M; citation_author=Moustsen-Helms  IR; citation_author=Valentiner-Branth  P;  citation_journal_title=Lancet Infect Dis;  citation_year=2025;  citation_volume=25;  citation_issue=12;  citation_pages=1293-1302; ",
        "citation_title=COVID-19 vaccine effectiveness against medically attended symptomatic SARS-CoV-2 infection among target groups in Europe, October 2024-January 2025, VEBIS primary care network.; citation_author=European Primary Care VE Group; citation_author=Laniece Delaunay  C; citation_author=Verdasca  N; citation_author=Monge  S;  citation_journal_title=Influenza Other Respir Viruses;  citation_year=2025;  citation_volume=19;  citation_issue=5; ",
        "Wiegand R,Fireman B,Najdowski M,Tenforde M,Link-Gelles R,Ferdinands J. Bias and negative values of COVID-19 vaccine effectiveness estimates from a test-negative design without controlling for prior SARS-CoV-2 infection.  Nat Commun. 2024 ; 15 ( 1 ): 10062. doi: 10.1111/irv.70120 39567531 ",
        "citation_title=Examining bias from differential depletion of susceptibles in vaccine effectiveness estimates in settings of waning.; citation_author=Kahn  R; citation_author=Feikin  DR; citation_author=Wiegand  RE; citation_author=Lipsitch  M;  citation_journal_title=Am J Epidemiol;  citation_year=2024;  citation_volume=193;  citation_issue=1;  citation_pages=232-234; ",
        "citation_title=Integrating genomic data into test-negative designs for estimating lineage-specific COVID-19 vaccine effectiveness.; citation_author=Ma  KC; citation_author=Surie  D; citation_author=Dean  N; citation_author=Paden  CR; citation_author=Thornburg  NJ; citation_author=Dawood  FS;  citation_journal_title=medRxiv; ",
        "citation_title=KP.2-based monovalent mRNA vaccines robustly boost antibody responses to SARS-CoV-2.; citation_author=Wang  Q; citation_author=Mellis  IA; citation_author=Wu  M;  citation_journal_title=Lancet Infect Dis;  citation_year=2025;  citation_volume=25;  citation_issue=3;  citation_pages=e133-e134; ",
        "citation_title=The KP.2-adapted COVID-19 vaccine improves neutralising activity against the XEC variant.; citation_author=Suthar  MS; citation_author=Manning  KE; citation_author=Ellis  ML;  citation_journal_title=Lancet Infect Dis;  citation_year=2025;  citation_volume=25;  citation_issue=3;  citation_pages=e122-e123; ",
        "citation_title=Impact of JN.1 booster vaccination on neutralisation of SARS-CoV-2 variants KP.3.1.1 and XEC.; citation_author=Arora  P; citation_author=Happle  C; citation_author=Kempf  A;  citation_journal_title=Lancet Infect Dis;  citation_year=2024;  citation_volume=24;  citation_issue=12;  citation_pages=e732-e733; ",
        "citation_title=Antigenic and virological characteristics of SARS-CoV-2 variants BA.3.2, XFG, and NB.1.8.1.; citation_author=Guo  C; citation_author=Yu  Y; citation_author=Liu  J;  citation_journal_title=Lancet Infect Dis;  citation_year=2025;  citation_volume=25;  citation_issue=7;  citation_pages=e374-e377; ",
        "citation_title=Antibody evasion and receptor binding of SARS-CoV-2 LP.8.1.1, NB.1.8.1, XFG, and related subvariants.; citation_author=Mellis  IA; citation_author=Wu  M; citation_author=Hong  H;  citation_journal_title=bioRxiv; ",
        "citation_title=Do existing COVID-19 vaccines need to be updated in 2025?; citation_author=Mellis  IA; citation_author=Wu  M; citation_author=Wang  Q;  citation_journal_title=bioRxiv; ",
        "citation_title=Host cell entry and neutralisation sensitivity of the emerging SARS-CoV-2 variant LP.8.1.; citation_author=Zhang  L; citation_author=Kempf  A; citation_author=Nehlmeier  I;  citation_journal_title=Lancet Infect Dis;  citation_year=2025;  citation_volume=25;  citation_issue=4;  citation_pages=e196-e197; ",
        "citation_title=Virological characteristics of the SARS-CoV-2 LP.8.1 variant.; citation_author=Genotype to Phenotype Japan (G2P-Japan) Consortium; citation_author=Chen  L; citation_author=Kaku  Y; citation_author=Okumura  K;  citation_journal_title=Lancet Infect Dis;  citation_year=2025;  citation_volume=25;  citation_issue=4; ",
        "Evaluation of COVID-19 vaccine effectiveness: interim guidance. World Health Organization. March 17, 2021. Accessed August 1, 2025. https://www.who.int/publications/i/item/WHO-2019-nCoV-vaccine_effectiveness-measurement-2021.1 ",
        "Center for Biologics Evaluation. Research. COVID-19 vaccines (2025-2026 formula) for use in the United States beginning in fall 2025. US Food and Drug Administration. May 22, 2025. Accessed May 27, 2025. https://www.fda.gov/vaccines-blood-biologics/industry-biologics/covid-19-vaccines-2025-2026-formula-use-united-states-beginning-fall-2025 "
      ],
      "twitter:card": "summary_large_image",
      "ogTitle": "Estimated 2024-2025 COVID-19 Vaccine Effectiveness Against Severe COVID-19",
      "twitter:site": "@JAMANetworkOpen",
      "citation_fulltext_world_readable": "",
      "citation_xml_url": "https://datafeed.jamanetwork.com/journals/jamanetworkopen/xml/2844612",
      "ogImage": "https://cdn.jamanetwork.com/ama/content_public/journal/jamanetworkopen/939778/zoi251532t1_1769460396.19957.png?Expires=2147483647&Signature=emOdhkcQzGnRCLvfjHQDCQyC5Pfxrz5srfaEbJ~LfUQquCgC6QkzpIcqHuX1-xypdbOh9j8PUq40QojsTniYrMZCr1zhDL40JOdN9U~Fc-zywpgSRCoe3E6Vdh3Bx8T7GFGYYcm4XQlYjL7B0xxlXBY-D-A3kOoU2i5WmKb388KyAF~C1-qxu8RuOiJ7Ck3gtZAd5J5DWax~hEmTbFaPwGX~MIEXa2WyjCo6wAh4wlGHzoOMBOJ9fLGPRRyqzaMlr-eaM-9~wdNt7OqBpFQtwiiKmBkOz77WmxMatNn5NV1YQezxftScFjKqzX60M0fe4ARWCGhdLvJlS3jYBR5OQA__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA",
      "og:title": "Estimated 2024-2025 COVID-19 Vaccine Effectiveness Against Severe COVID-19",
      "citation_doi": "10.1001/jamanetworkopen.2025.57415",
      "citation_publisher": "American Medical Association",
      "description": "This case-control study estimates vaccine effectiveness of the 2024-2025 COVID-19 vaccines against severe COVID-19 and investigates whether it varied by",
      "publish_date": "2026-02-03",
      "viewport": "width=device-width, initial-scale=1",
      "citation_lastpage": "e2557415",
      "citation_firstpage": "e2557415",
      "ogDescription": "This case-control study estimates vaccine effectiveness of the 2024-2025 COVID-19 vaccines against severe COVID-19 and investigates whether it varied by SARS-CoV-2 lineage or spike protein mutations.",
      "citation_issue": "2",
      "citation_author": [
        "Kevin C. Ma",
        "Alexander Webber",
        "Adam S. Lauring",
        "Emily Bendall",
        "Leigh K. Papalambros",
        "Basmah Safdar",
        "Adit A. Ginde",
        "Ithan D. Peltan",
        "Samuel M. Brown",
        "Manjusha Gaglani",
        "Shekhar Ghamande",
        "Cristie Columbus",
        "Nicholas M. Mohr",
        "Kevin W. Gibbs",
        "David N. Hager",
        "Matthew E. Prekker",
        "Michelle N. Gong",
        "Amira Mohamed",
        "Nicholas J. Johnson",
        "Akram Khan",
        "Catherine L. Hough",
        "Abhijit Duggal",
        "Jennifer G. Wilson",
        "Nida Qadir",
        "Steven Y. Chang",
        "Christopher Mallow",
        "Laurence W. Busse",
        "Jennie H. Kwon",
        "Matthew C. Exline",
        "Ivana A. Vaughn",
        "Mayur Ramesh",
        "Jarrod M. Mosier",
        "Aleda M. Leis",
        "Estelle S. Harris",
        "Adrienne Baughman",
        "Sydney A. Cornelison",
        "Paul W. Blair",
        "Cassandra A. Johnson",
        "Nathaniel M. Lewis",
        "Sascha Ellington",
        "Todd W. Rice",
        "Carlos G. Grijalva",
        "H. Keipp Talbot",
        "Jonathan D. Casey",
        "Natasha Halasa",
        "James D. Chappell",
        "Yuwei Zhu",
        "Wesley H. Self",
        "Fatimah S. Dawood",
        "Diya Surie",
        "Investigating Respiratory Viruses in the Acutely Ill (IVY) Network",
        "Tresa McNeal",
        "Nicole Calhoun",
        "Jocelyn Cravens",
        "Kempapura Murthy",
        "Leah Odame-Bamfo",
        "Spencer Rose",
        "Michael Smith",
        "Barbara Hairston",
        "Amanda McKillop",
        "Victoria Harkins Walston",
        "Robert L. Gottlieb",
        "Catherine Raver",
        "Sydney Buehrig",
        "Priyanka Rana",
        "Ashley Bychkowski",
        "Symone Dunkley",
        "Denisse Mariscal",
        "Tammy Fisher",
        "Daniela Gonzalez",
        "Therissa Grefsrud",
        "Mariana Hurutado-Rodriguez",
        "Gabriela Perez",
        "Jay Steingrub",
        "Lesley De Souza",
        "Scott Ouellette",
        "Cynthia Kardos",
        "Rae Lynn Defeo",
        "Nathan I. Shapiro",
        "Michael Bolstad",
        "Brianna Coviello",
        "Robert Ciottone",
        "Arnaldo Devilla",
        "Ana Grafals",
        "Conor Higgins",
        "Carlo Ottanelli",
        "Kimberly Redman",
        "Douglas Scaffidi",
        "Alexander Weingart",
        "Omar Mehkri",
        "Megan Mitchell",
        "Zachary Griffith",
        "Connery Brennan",
        "Kiran Ashok",
        "Bryan Poynter",
        "Laurence Busse",
        "William Bender",
        "Caitlin ten Lohuis",
        "Laurynn Giles",
        "Mary O'Rourke",
        "Anne Frosch",
        "Audrey Hendrickson",
        "Julianna Prohofsky",
        "Kowsar Hurreh",
        "Joanna Kuo",
        "Gina Maki",
        "Jaskiran Bansal",
        "Michael Garcia",
        "Alycia Lilla",
        "Catherine McKeon",
        "Maria Santana-Garces",
        "Tanisha Shack",
        "Sindhuja Koneru",
        "Shruti Tirumala",
        "Joslyn Bassett",
        "Shandi Poulson",
        "Vineela Thumma",
        "Minh Phan",
        "Safa Saeed",
        "Sarah Karow",
        "Maryiam Khan",
        "Gabrielle Swoope",
        "Brooke Lee",
        "Amane Rasul",
        "Kirstina Luikart",
        "Tyler Haley",
        "Amer Charif",
        "Thomas Sturges",
        "Ibrahim Abu Hammad",
        "Rashil Madan",
        "Jenny Chan",
        "Connie Tran",
        "Davika Dige",
        "Anabelle Blue",
        "Amy Segura",
        "Riya Matthew",
        "Adrian Hernandez",
        "Emily Tribbett",
        "Genesis Briceno",
        "Grace Kyin-Ye Tam",
        "Vanessa Pitre",
        "Samantha Ferguson",
        "Cynthia Perez",
        "Alexandra June Gordon",
        "Leonard Basobas",
        "Lily Lau",
        "Cameron Hypes",
        "Karen Lutrick",
        "Beth Salvagio Campbell",
        "Cody Tran",
        "Sukantha Chandrasekaran",
        "Omai Garner",
        "Samantha Simon",
        "Amanda Martinez",
        "Amy Sullivan",
        "Laura Aguilar-Marquez",
        "Erika Alor",
        "Yvette Evans",
        "Jacob Rademacher",
        "Nicholas Mohr",
        "Anne Zepeski",
        "Paul Nassar",
        "Noble Briggs",
        "Jacob Hampton",
        "Cathy Fairfield",
        "Carolina Rivas",
        "Weronika Damek Valvano",
        "Anne Kaniclides",
        "Rebecca Fong",
        "Mildred Wallace",
        "Chiraag Balsara",
        "Rachel Truson",
        "Regina Lehmann",
        "Abigail Carolan",
        "Izza Imran",
        "Jozyan Ujmaya",
        "William J. Fitzsimmons",
        "Rylie McBride",
        "Bryce Bosworth",
        "Bryce Heslop",
        "Joshua Acidera",
        "Maile Mckeown",
        "Leenay Coughlin",
        "Frances Nagore",
        "Dylan Clark",
        "Karen F. Miller",
        "Jakea Johnson",
        "Kelsey N. Womack",
        "Jillian Rhoads",
        "Colleen Ratcliff",
        "Ine Sohn",
        "Cara Lwin",
        "Julio Angulo",
        "Stacy Batey",
        "Shanice Cummings",
        "Abby Fink",
        "Claudia Guevara",
        "Jennifer Luther",
        "Rendie McHenry",
        "Bryan Peterson",
        "Neekar Rashid",
        "Wanderson Rezende",
        "Kalee Rumfelt",
        "Laura Short",
        "Kevin Gibbs",
        "Hannah Strait",
        "Bijal Parikh",
        "Carleigh Samuels",
        "Lucy Vogt",
        "Caroline O'Neil",
        "Alyssa Valencia",
        "Francesca Yerbic",
        "Olivia Arter",
        "Akshay Saluja",
        "Elianora Ovchiyan",
        "Sachina Mensah",
        "Kim Vu",
        "David McDonald",
        "Regine Burton",
        "Anirudh Goyal",
        "Ivan Valesquez",
        "Arda Yigitkanli",
        "Kimberly Manchester"
      ],
      "citation_pdf_url": "https://jamanetwork.com/journals/jamanetworkopen/articlepdf/2844612/ma_2026_oi_251532_1769460395.55231.pdf",
      "twitter:image": "https://cdn.jamanetwork.com/ama/content_public/journal/jamanetworkopen/939778/zoi251532t1_1769460396.19957.png?Expires=2147483647&Signature=emOdhkcQzGnRCLvfjHQDCQyC5Pfxrz5srfaEbJ~LfUQquCgC6QkzpIcqHuX1-xypdbOh9j8PUq40QojsTniYrMZCr1zhDL40JOdN9U~Fc-zywpgSRCoe3E6Vdh3Bx8T7GFGYYcm4XQlYjL7B0xxlXBY-D-A3kOoU2i5WmKb388KyAF~C1-qxu8RuOiJ7Ck3gtZAd5J5DWax~hEmTbFaPwGX~MIEXa2WyjCo6wAh4wlGHzoOMBOJ9fLGPRRyqzaMlr-eaM-9~wdNt7OqBpFQtwiiKmBkOz77WmxMatNn5NV1YQezxftScFjKqzX60M0fe4ARWCGhdLvJlS3jYBR5OQA__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA",
      "product_code": [
        "covid19",
        "ALL_CONTENT",
        "OPEN_ACCESS",
        "NML",
        "KBART_CURRENT_TITLES",
        "EML",
        "J_2844612",
        "I_939778"
      ],
      "fb:pages": [
        "87087958340",
        "122228711814384",
        "1648414928738217",
        "117506346528",
        "97538728726",
        "114116793520",
        "100679858757",
        "759822190741773",
        "100265333750",
        "234770525256",
        "98784919862",
        "120829458202",
        "124842870398",
        "110245330325636"
      ],
      "favicon": "https://cdn.jamanetwork.com/UI/app/img/favicons/jamanetworkopen/favicon-192x192.png",
      "scrapeId": "019f4a90-610b-7018-8e7e-155a50213aee",
      "sourceURL": "https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2844612",
      "url": "https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2844612",
      "statusCode": 200,
      "contentType": "text/html; charset=utf-8",
      "proxyUsed": "basic",
      "cacheState": "hit",
      "cachedAt": "2026-07-10T05:42:20.440Z",
      "creditsUsed": 5,
      "concurrencyLimited": false
    }
  }
}

Assistant: 

Tool: {
  "success": true,
  "data": {
    "json": {
      "benefits": {
        "effectiveness": [
          {
            "ve_percentage": 70,
            "time_period": "first 2 months after vaccination",
            "population": "adults ages 18 and older",
            "conclusion": "The 2023–2024 COVID-19 vaccines reduced the risk of critical illness from COVID-19 by almost 70%.",
            "study_reference": "[6](https://www.cdc.gov/covid/vaccines/benefits.html#cdcreference_6)",
            "date": "June 10, 2025"
          },
          {
            "ve_percentage": 50,
            "time_period": "10 months after vaccination",
            "population": "adults ages 18 and older",
            "conclusion": "Protection decreased over time with vaccines reducing critical illness risk by about 50%.",
            "study_reference": "[6](https://www.cdc.gov/covid/vaccines/benefits.html#cdcreference_6)",
            "date": "June 10, 2025"
          },
          {
            "ve_percentage": 50,
            "time_period": "first 2 months after vaccination",
            "population": "adults ages 18 and older",
            "conclusion": "The 2023–2024 COVID-19 vaccines reduced the risk of COVID-19 hospitalization by about 50%.",
            "study_reference": "[6](https://www.cdc.gov/covid/vaccines/benefits.html#cdcreference_6)",
            "date": "June 10, 2025"
          },
          {
            "ve_percentage": 30,
            "time_period": "10 months after vaccination",
            "population": "adults ages 18 and older",
            "conclusion": "During the 10 months after vaccination, the vaccines reduced hospitalization risk by about 30%.",
            "study_reference": "[6](https://www.cdc.gov/covid/vaccines/benefits.html#cdcreference_6)",
            "date": "June 10, 2025"
          },
          {
            "ve_percentage": 50,
            "time_period": "first 2 months after vaccination",
            "population": "adults ages 18 and older",
            "conclusion": "Vaccines reduced the risk of urgent care and emergency department visits by about 50%.",
            "study_reference": "[6](https://www.cdc.gov/covid/vaccines/benefits.html#cdcreference_6)",
            "date": "June 10, 2025"
          },
          {
            "ve_percentage": 67,
            "time_period": "first 2 months after vaccination",
            "population": "adults 65 years and older",
            "conclusion": "The 2023–2024 COVID-19 vaccines reduced the risk of critical illness among older adults by about 67%.",
            "study_reference": "[6](https://www.cdc.gov/covid/vaccines/benefits.html#cdcreference_6)",
            "date": "June 10, 2025"
          },
          {
            "ve_percentage": 40,
            "time_period": "4–6 months after vaccination",
            "population": "adults 65 years and older",
            "conclusion": "During 4–6 months after vaccination, the vaccines reduced critical illness risk by about 40%.",
            "study_reference": "[6](https://www.cdc.gov/covid/vaccines/benefits.html#cdcreference_6)",
            "date": "June 10, 2025"
          },
          {
            "ve_percentage": 36,
            "time_period": "first 2 months after vaccination",
            "population": "adults with a weakened immune system",
            "conclusion": "Vaccines reduced the risk of COVID-19 hospitalization for people with a weakened immune system by about 36%.",
            "study_reference": "[6](https://www.cdc.gov/covid/vaccines/benefits.html#cdcreference_6)",
            "date": "June 10, 2025"
          },
          {
            "ve_percentage": 54,
            "time_period": "first 3 months of life",
            "population": "infants whose mothers were vaccinated during pregnancy",
            "conclusion": "Maternal vaccination reduced the risk of COVID-19-related hospitalization by around 54% among infants.",
            "study_reference": "[11](https://www.cdc.gov/covid/vaccines/benefits.html#cdcreference_11)",
            "date": "June 10, 2025"
          },
          {
            "ve_percentage": 65,
            "time_period": "first 2 months after vaccination",
            "population": "children ages 9 months to 4 years",
            "conclusion": "Vaccines reduced the risk of COVID-19-associated emergency room and urgent care visits by around 65%.",
            "study_reference": "[6](https://www.cdc.gov/covid/vaccines/benefits.html#cdcreference_6)",
            "date": "June 10, 2025"
          },
          {
            "ve_percentage": 70,
            "time_period": "first 2 months after vaccination",
            "population": "children ages 5–17 years",
            "conclusion": "Vaccines reduced the risk by about 70%.",
            "study_reference": "[6](https://www.cdc.gov/covid/vaccines/benefits.html#cdcreference_6)",
            "date": "June 10, 2025"
          }
        ]
      }
    },
    "metadata": {
      "og:updated_time": "2026-03-02T12:48:17-05:00",
      "viewport": "width=device-width, initial-scale=1, shrink-to-fit=no",
      "cdc:page_type": "cdc_dfe",
      "cdc:last_published": "2026-03-02T12:49:54Z",
      "ogSiteName": "Covid",
      "mobile-web-app-capable": "yes",
      "cdc:last_reviewed": "January 3, 2025",
      "cdc:version": "4.25.12",
      "twitter:description": "Find out why you should get the COVID-19 vaccine and how it protects you from getting sick.",
      "cdc:page_origin": "dfe",
      "og:image:type": "image/jpeg",
      "ogImage": "https://www.cdc.gov/covid/media/images/2024/11/RS2649_RMN7_Flu_Vaccine_Stock_Photoshoot_2022_041_scr.jpg?_=50746",
      "ogUrl": "https://www.cdc.gov/covid/vaccines/benefits.html",
      "cdc:content_source": "",
      "twitter:creator": "@CDCgov",
      "og:url": "https://www.cdc.gov/covid/vaccines/benefits.html",
      "apple-mobile-web-app-capable": "yes",
      "cdc:maintained_by": "",
      "twitter:title": "Benefits of Getting Vaccinated",
      "cdc:build": "5475",
      "ogTitle": "Benefits of Getting Vaccinated",
      "title": "Benefits of Getting Vaccinated | Covid | CDC",
      "cdc:dfe_content_type": "cdc_generic",
      "cdc:dfe_version": "0.3",
      "cdc:dfe_content_type_version": "1.2.5",
      "cdc:wcms_build": "4.25.12 - b.5475",
      "og:site_name": "Covid",
      "twitter:image:src": "https://www.cdc.gov/covid/media/images/2024/11/RS2649_RMN7_Flu_Vaccine_Stock_Photoshoot_2022_041_scr.jpg?_=50746",
      "twitter:card": "summary",
      "DC.date": "2026-03-02T12:48:17Z",
      "twitter:url": "https://www.cdc.gov/covid/vaccines/benefits.html",
      "article:author": "CDC",
      "og:image": "https://www.cdc.gov/covid/media/images/2024/11/RS2649_RMN7_Flu_Vaccine_Stock_Photoshoot_2022_041_scr.jpg?_=50746",
      "ogDescription": "Find out why you should get the COVID-19 vaccine and how it protects you from getting sick.",
      "og:type": "article",
      "twitter:site": "@CDCgov",
      "fb:app_id": "205691699516606",
      "og:description": "Find out why you should get the COVID-19 vaccine and how it protects you from getting sick.",
      "cdc:template_version": "5.0",
      "description": "Find out why you should get the COVID-19 vaccine and how it protects you from getting sick.",
      "language": "en-us",
      "og:title": "Benefits of Getting Vaccinated",
      "msapplication-TileColor": "#0056b3",
      "theme-color": "#0056b3",
      "og:author": "CDC",
      "cdc:first_published": "July 16, 2024",
      "robots": "index, archive",
      "cdc:last_updated": "June 10, 2025",
      "cdc:content_id": "2520",
      "favicon": "https://www.cdc.gov/TemplatePackage/5.0/img/favicon/favicon-32x32.png",
      "scrapeId": "019f4a91-3d2c-746a-b992-63c8e2dd3f3c",
      "sourceURL": "https://www.cdc.gov/covid/vaccines/benefits.html",
      "url": "https://www.cdc.gov/covid/vaccines/benefits.html",
      "statusCode": 200,
      "contentType": "text/html",
      "proxyUsed": "basic",
      "cacheState": "hit",
      "cachedAt": "2026-07-10T05:47:07.892Z",
      "creditsUsed": 5,
      "concurrencyLimited": false
    }
  }
}

Assistant: 

Tool: Plan updated successfully.

Assistant: 

Tool: Plan updated successfully.

Assistant: # Effectiveness of COVID-19 Vaccines in Reducing Severe Disease Among Adults in the United States

## Executive Summary

COVID-19 vaccines continue to provide meaningful protection against severe disease outcomes among adults in the United States, though absolute effectiveness has moderated compared with the early pandemic period due to viral evolution, hybrid immunity, and waning. 

Authoritative data from CDC networks (VISION and IVY) and a large multicenter JAMA Network Open study show that the 2024–2025 COVID-19 vaccine formulations reduced the risk of COVID-19-associated hospitalization by approximately 40–46% among adults (higher in older adults) and provided even stronger protection against the most severe outcomes (invasive mechanical ventilation or death: ~79%). Protection against emergency department/urgent care visits was lower (~33%). Earlier 2023–2024 formulations reduced hospitalization risk by ~50% and critical illness by ~70% in the first 2 months, with gradual waning. 

These findings, drawn exclusively from CDC MMWR reports, CDC vaccine benefits summaries, and JAMA Network Open analyses using test-negative designs, consistently support vaccination as an effective tool for reducing severe COVID-19 among U.S. adults, particularly those aged ≥65 years and those at elevated risk. Protection is additional to any prior infection or vaccination and remains clinically relevant against circulating JN.1-lineage descendants.

## Evidence Table

| Source | Publication Date | Study Type | Main Conclusion |
|--------|------------------|------------|-----------------|
| CDC MMWR (Link-Gelles et al.; VISION & IVY Networks) | February 27, 2025 (updated later) | Test-negative design observational study (Sep 2024–Jan 2025) | 2024–2025 COVID-19 vaccine VE: 33% (95% CI 28–38%) against ED/UC visits (adults ≥18); 45% (36–53%) against hospitalization in immunocompetent adults ≥65 (VISION); 46% (26–60%) in IVY Network immunocompetent ≥65; 40% (21–54%) in immunocompromised ≥65. Provides additional protection vs. no receipt of the updated dose. |
| JAMA Network Open (Ma et al.; IVY Network) | February 3, 2026 | Multicenter test-negative case-control study (26 hospitals, 20 states; Sep 1, 2024–Apr 30, 2025) | 2024–2025 COVID-19 vaccines: VE 40% (95% CI 27–51%) against COVID-19-associated hospitalization; 79% (55–92%) against invasive mechanical ventilation or death. Protection sustained through 90–179 days; varied somewhat by JN.1 sublineage. |
| CDC COVID-19 Vaccines Benefits page | Last updated June 10, 2025 (content reviewed earlier) | Summary of CDC observational VE data (primarily 2023–2024 season) | 2023–2024 vaccines reduced hospitalization risk ~50% and critical illness ~70% in first 2 months among adults ≥18 (waning to ~30% and ~50% by 10 months); ~67% reduction in critical illness among ≥65 in first 2 months; ~36% against hospitalization in immunocompromised adults. |

## Confidence Assessment

**High confidence** in the overall conclusion that COVID-19 vaccines reduce severe disease (hospitalization and critical outcomes) among U.S. adults. 

- Evidence comes from large, multi-state CDC surveillance networks (VISION, IVY) and peer-reviewed JAMA Network Open analyses using established test-negative designs with adjustment for confounders.  
- Consistency across independent networks and seasons (2023–2024 and 2024–2025) strengthens reliability.  
- Estimates are precise enough for public-health decision-making, with clear confidence intervals and stratification by age and immune status.  
- Limitations of observational designs (residual confounding, prior infection effects) are well-recognized and partially mitigated by the methods used.  

Confidence is slightly lower for precise long-term durability beyond 6 months and for very new sublineages, where data are still accumulating.

## Limitations

- Observational (test-negative) designs cannot fully eliminate residual confounding (e.g., healthcare-seeking behavior, unmeasured comorbidities, or differential prior infection).  
- Most recent estimates focus on additional protection from the 2024–2025 dose rather than absolute protection from any vaccination history.  
- Waning of protection over time is documented; estimates are time-since-vaccination dependent.  
- Effectiveness varies by age, immune status, and circulating variant (lower against some later JN.1 descendants).  
- Data primarily cover adults seeking medical care; milder community outcomes and very long-term effects are outside the scope of the reviewed sources.  
- No randomized controlled trial data from the 2024–2025 season were available in the prioritized sources; reliance is on real-world evidence.  
- Research was limited to three pages from CDC and JAMA as per workflow constraints; broader historical meta-analyses or NEJM/NIH primary papers were not re-extracted.

## Interesting Findings

- Protection is **strongest against the most severe endpoints**: VE reached 79% against invasive mechanical ventilation or death—substantially higher than against any hospitalization (40%).  
- Updated 2024–2025 vaccines still delivered clinically meaningful benefit even after years of population hybrid immunity and against highly evolved JN.1-lineage viruses.  
- Older adults (≥65) consistently showed higher absolute VE against hospitalization (~45–46%) than the broader adult population for milder severe outcomes.  
- Protection against hospitalization remained relatively stable through 90–179 days post-vaccination in the JAMA analysis, contrary to faster waning sometimes observed for infection prevention.

## Sources / References

1. Link-Gelles R, et al. Interim Estimates of 2024–2025 COVID-19 Vaccine Effectiveness Among Adults Aged ≥18 Years — VISION and IVY Networks, September 2024–January 2025. *MMWR Morb Mortal Wkly Rep*. 2025;74(6). https://www.cdc.gov/mmwr/volumes/74/wr/mm7406a1.htm  
2. Ma KC, et al. Estimated Effectiveness of 2024-2025 COVID-19 Vaccination Against Severe COVID-19. *JAMA Netw Open*. 2026;9(2):e2557415. https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2844612  
3. Centers for Disease Control and Prevention. Benefits of Getting Vaccinated. Updated June 10, 2025. https://www.cdc.gov/covid/vaccines/benefits.html

User: List some more

Assistant: 

Tool: Plan updated successfully.
