**Title: cATO For Software Authorisation

---

layout: post

title: cATO For Software Authorisation

categories: [NIST, ISM, GRC, SSDF, SDLC, DevSecOps]

---
Recently I had a conversation with a colleague discussing continuous Authority To Operate (cATO), and quickly realised we were actually talking about different things. What they were describing was a way to expedite the approval of software within a secure system by using a hardened software development pipeline. Where, on the other hand I was discussing the need to move away from 3 year re-authorisation (previously accreditation) cycles and move to a continuous model. I’ll discuss software authorisation here, and system re-authorisation cycles in my next post.

The process of testing and approving software applications to be run in a secure system is outlined in NIST’s [Software Supply Chain Security Guidance](https://www.nist.gov/itl/executive-order-14028-improving-nations-cybersecurity/software-supply-chain-security-guidance). NIST provides three key reasons for improving Software Supply Chain Security:
1. To reduce the number of vulnerabilities in released software, 
2. To reduce the potential impact of the exploitation of undetected or unaddressed vulnerabilities, and 
3. To address the root causes of vulnerabilities to prevent recurrences. 

The key document for companies providing software for United States Federal Government (US Fed Gov) is the [Secure Software Development Framework](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-218.pdf)(SSDF). The SSDF recommends that:
1. Organisations should integrate the SSDF throughout their existing software development practices, 
2. Express their secure software development requirements to third-party suppliers using SSDF conventions, and 
3. Acquire software that meets the practices described in the SSDF. 
Due to the NIST recommendation that US Fed Gov organisations acquire software that meets the practices in the SSDF it has meant that software development companies need to implement these practices and be able to provide evidence of doing so in order to have their software be accepted for government procurement.

An understanding of what is required can be had by looking at a pre-made and secured software pipeline such as the one provided by [Second Front]([https://www.secondfront.com](https://www.secondfront.com/)). Second Front have configured their software pipeline within a cloud environment and offer development tenancies within that environment which can connect to a centralised DevSecOps Toolchain. The SecondFront Toolchain, referred to as Game Warden will then conduct the automated testing, provide the immutable attestation documentation and deliver a software product which can be considered “compliant” with the SSDF and is able to be hosted as a SaaS platform for delivery to US Fed Gov Clients.

But what about here in Australia? The [Information Security Manual](https://www.cyber.gov.au/resources-business-and-government/essential-cyber-security/ism) (ISM) does not require the use of software that meets the SSDF requirements. The Supply Chain Risk Management portion of the ISM comes under [Procurement and Outsourcing](https://www.cyber.gov.au/sites/default/files/2023-12/05.%20ISM%20-%20Guidelines%20for%20Procurement%20and%20Outsourcing%20%28December%202023%29.pdf) and comes down to understanding the supplier themselves. The ISM recommends that:
1. Suppliers have demonstrated a commitment to security in their products
2. Suppliers have demonstrated a commitment to transparency for their products
3. Suppliers have a strong track record of maintaining the security of their own systems and cyber supply chains
4. Applications are delivered in a manner that maintains their integrity, and
5. The integrity and authenticity of applications are assessed as part of acceptance of products and services.

The openness of the ISM means that it’s open to interpretation, and requires significant risk management by organisations that are trying to implement the recommendations. For example, there have now been numerous high level CVEs in Atlassian’s almost ubiquitous Confluence and Jira software. Does that mean that Australian organisations are going to stop using them? Highly unlikely. Should the Cyber Security teams at these organisations be adjusting their risk management profile for Optus after their second large incident in as many years? Effectively, no, as long as an organisation can identify who is supplying their software products, can show a risk assessment for each based on some metrics that include security, transparency, and previous cyber incidents, then they meet the ISM’s requirements and would likely have their controls deemed Effective by an Independent Registered Assessor Program (IRAP) assessment.

Arguably the ISM actually pushes Australian organisations to deal with well-known, reputable companies due to their clearer history. Are the ISM controls actually enabling organisations to achieve better outcomes? They don’t seem to meet the NIST’s reasons for conducting Supply Chain Risk Management. Should the ISM be looking to require compliance against the SSDF or, implement an Australian equivalent? 
