---
layout: page
title: Understanding Privacy and Confidentiality in the Context of Open Data
---

As agencies evaluate their data assets for inclusion in open data projects, they must separate confidential data from data that can be shared. When they tackled this problem, the California Health and Human Services Agency adapted from a three-tiered taxonomy used by [New York State](http://ny.github.io/open-data-handbook/). Under this system data falls into three broad classes: (I) data that qualifies as public in its current form; (II) data that could be made public, but would first need to be altered to protect privacy; and (III) data that is sensitive and confidential, and must remain so. Although agencies will spend most of their time with respect to privacy on data falling into tier II, categorizing data assets into all three tiers requires balancing between two core values: transparency and privacy. Doing so requires knowledge of the legal and policy requirements regarding privacy and confidentiality, as well as the current science of disclosure limitation.

### Public vs Confidential Data

Much of an Agency’s data is public. [The California Public Records Act (CPRA)](http://ag.ca.gov/publications/summary_public_records_act.pdf) establishes that the public has a fundamental right to access information concerning the conduct of public business. This has been described as a presumption of openness unless specifically exempted. Although not comprehensive, common Public Records Act exemptions include information that would – if published by an agency –constitute an invasion of personal privacy, impair contractual obligations or collective bargaining negotiations, harm law enforcement or judicial proceedings, expose trade secrets, or endanger public safety.

In particular, state agencies have a constitutional responsibility to protect privacy. [Article 1, Section 1 of the California Constitution](http://www.leginfo.ca.gov/const-toc.html) includes an inalienable right to privacy. There are also legislative, regulatory, and contractual mandates that require state government to maintain confidentiality and protect the privacy of Californians. Depending on the type of data held by an agency, the data may also be subject to Federal confidentiality rules.

[The California Information Practices Act of 1977 (CIPA)](http://leginfo.legislature.ca.gov/faces/codes_displayexpandedbranch.xhtml?tocCode=CIV&division=3.&title=1.8.&part=4.&chapter=1.&article=) expands the constitutional protection of privacy and places additional limits on what personal information state agencies may collect, how they manage it, and what they publish. This includes civil and legal liability for an agency that fails to comply with the Act, and may include civil and criminal liability for state employees that disclose data they should have reasonably known was obtained from personal information. 

Some limitations of the act are the failure to specifically address the difference between information that directly identifies an individual (i.e. name, social security number, etc), and information that could be used to identify an individual by pairing it with other information (i.e. date and place of birth could be paired with public birth records to identify an individual). Likewise, it does not provide any specific guidance on processes to follow when clearing data for publication. More recent legislation typically includes such “Safe Harbor” provisions, so that agencies have a better understanding about how to protect themselves against liability from unintentional disclosure.

In addition to state requirements, federal law also governs state data disclosure.  Two well-known examples, the *Health Information Portability and Accountability Act* (HIPAA) and the *Family Educational Rights and Privacy Act* (FERPA) outline both the types of data that are confidential, as well as de-identification methods that agencies can use to publish data without compromising the privacy of individuals. For instance, HIPAA provides two distinct ways to de-identify prior to publication, the “Expert Determination” (Section 164.514[b][1]) and “Safe Harbor Method” (Section 164.514[b][2]). For expert determination, disclosure limitation specialists must determine that there is no more than a “very small” risk that someone could use the information to identify specific individuals. In a Safe Harbor evaluation, the Agency removes 18 specific types of personal identifiers and certifies that the published information could not – alone or when combined with other data – be used to identify individuals. 

Legislation can also include specific carve-outs for public disclosure; for example, FERPA allows the disclosure of certain personally identifiable information when published in a directory. Yearbooks and student directories are two common cases covered under this exception. Finally, FERPA and other privacy laws often place fewer restrictions on data provided voluntarily, such as in optional surveys.

### Disclosure Limitation

Using methods such as Expert Determination and Safe Harbor, and by anonymizing, masking or otherwise de-identifying data, agencies can make more information publicly available without compromising the privacy rights of Californians. These techniques involve simple deletion (dropping fields with confidential information), masking (scrambling or removing part of the field to make the information no longer sensitive), or noise infusion (adding random variance to numeric data), for example.

It is still possible to re-identify masked data by comparing published fields with other public data sets that include the same identifiers. For example, California voter data is considered public data, and includes names, addresses, and birth dates. Telephone directories, yearbooks and court records also contain information that could be used for re-identification. In addition, agencies that wish to minimize the risk of data re-identification must also consider newer sources of public information such as social media profiles and other digital records.

An entity attempting to re-identify data may do so broadly, trying to re-identify substantial portions of a complete data set; or by targeting a specific individual believed to be in the data set. Because a single individual is being targeted, it is easier to gather additional reference data that the entity can use to re-identify the record. The targets of many of these types of attacks are often noteworthy or influential, such as when researchers re-identified Massachusetts Governor William Weld’s medical data from an insurance data set using his gender, birthdate, and zip code.

In all cases, however, disclosure limitation involves trade-offs. It is possible to lower the risk of disclosure by aggregating observations and/or adding masks to fields, but both of these actions reduce the value of the published data for those analyzing it. Agencies must balance between the right for citizens to be informed about the conduct of public business and an individual’s right to privacy. Departments must determine the correct level of de-identification and granularity for their community. 

Just as Agencies do today, if they cannot make data publicly available, an Agency may make data-sharing agreements with other government agencies or researchers in order to facilitate analysis in the area. 

### Changing Environment

Whatever methods of disclosure limitation an organization chooses, it is important to keep in mind that their effectiveness is dependent on the state of technology, social expectations about privacy, and the available datasets against which to match. These are all subject to change, meaning that any certification that a data set is suitably de-identified is time-limited. It is, therefore, very important to reassess the privacy of already published datasets at regular intervals.

The field of disclosure limitation is likewise evolving. One area of rapid change in California and across the nation is the emergence of photography and video created by new equipment such as traffic cameras, drones and body cameras. All three have been put into use by various state agencies as they adopt new technology to fulfill their mission. The use of inexpensive but high quality photographic and video recording equipment by governments has resulted in a dramatic increase in the volume of such data held by agencies. Determining how to hold, manage and publish such data is an ongoing discussion within government and it is likely to take time before a settled solution emerges.

###Third Party Vendors

If agencies store sensitive data off-site with third party vendors, it is important to consider the terms under which data is shared:

*	Security and data stewardship
*	Data collection
*	Data use, retention, disclosure and destruction
*	Data access
*	Modification, duration, and termination
*	Data breach responsibility

In general, it is more secure to only publish de-identified data to third party platforms; however, any time outside vendors have access to potentially confidential data it is necessary to explicitly identify the privacy concerns and remedies and to regularly assess privacy risks.  When negotiating contracts, provisions can be changed to take into account the specific privacy needs reflected in the data. Many services do not readily allow for such negotiation, however, relying on standardized “click to agree” contracts. These are especially common with free or low-cost cloud services – often because they intend to monetize the data and/or traffic some other way – and agencies should take care when using a service under such terms of service. The open data governance team should read and agree to such contracts. If they cannot sign-off because of specific clauses, they can contact the company and negotiate the terms of service individually.

Determining whether the information in a data set constitutes confidential material is not always obvious, instead requiring a balancing test of the rights to privacy against the interests of the public in access to the information. This makes it critical that the governance team includes individuals with the expertise necessary to make such determinations. Such experts can include data scientists with knowledge of disclosure limitation, agency legal counsel, and/or their PRA officers.

### Licensing and Terms of Service

When releasing data to the public, many agencies decide to apply formal terms of service and licensing rules to their portals. In these cases, portals either require users to explicitly agree to the terms and rules or they rely on implied consent. The California Health and Human Services portal relies on implied consent. Anyone may view data on the site, but the terms of service requires that any “reuse, publication, and/or distribution” of data must include an attribution back to the department that published the data. The terms of service also outlines the Agency’s acceptable use policy and includes clauses on limitation of liability and indemnification. The State Controller’s Office, which often posts data from local governments, includes statements that the information is “posted as submitted by the reporting entity” and notes that it does not take responsibility for accuracy of data provided by other entities. The Controller’s Office lists this information on the bottom of their open data site pages and also does not ask for users’ consent prior to accessing data. Other agencies, for example the Board of Equalization and the Franchise Tax Board, require users to explicitly agree to their terms of service before viewing the data on the portal. Each Agency publishing data will need to decide how they will approach this issue. The [Open Data Commons](http://opendatacommons.org/licenses/) provides several licensing options that Agencies may consider as a starting place. 


<!-- Pagination -->
<div class="pagination">
  <a class="pagination-item older" href="{{ site.baseurl }}/07-Government-Regulations">&laquo; Prev</a>
  <a class="pagination-item newer" href="{{ site.baseurl }}/09-Acknowledgements">Next &raquo;</a>
</div>

