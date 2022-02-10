# Companion Documentation for Uniper Inner Source License 

*Original document by Cornelius Schumacher, Schlomo Schapiro, 28.10.2019, DB Systel GmbH* \
*Adaptation by Tunay Okumus, 10.02.2022, Uniper SE*

## What is inner-source?

"Inner source" describes the approach of applying open source principles to software development within a company without publishing the program code outside the company. This makes it possible to benefit from the advantages of open source development models without making the development public and without abandoning the business model of selling software licenses.

Inner Source can thus lead to improved collaboration, increase development speed and quality, and help to reduce costs. This is particularly successful in situations where different parts of the company require software components with similar requirements, for example internal standard libraries, infrastructure components or development, test and deployment tools.

# Why a new software license?

Within a single company, Inner Source is primarily a new type of collaboration and does not require any special contracts or software licenses, since all authors and users of a software belong to the same company. In a group context, further challenges arise from the collaboration between the different independent group subsidiaries. The transfer of source code or binary packages between the different companies -- even in the same group -- needs a contractual arrangement and has to be reflected in the accounting of the companies.

The Uniper Inner Source License solves the contractual issues and creates a legally secure framework for collaboration between the group subsidiaries. Thus, the Uniper ISL makes a concrete contribution to the holistic optimization for the Uniper Group.

The financial aspects are not part of the consideration for the Uniper ISL. The license allows both the free transfer as a gift and the conclusion of additional contracts in which, for example, further development or support around the software licensed under the Uniper-ISL are agreed.

Since classic open source licenses only assume a donation of the software and have the goal of enabling and promoting the maximum public distribution of the software in the world, they are not applicable for collaboration according to open source principles within a corporate group. The Uniper ISL as a new license creates the bridge between these worlds and provides a legal framework for open source collaboration within the Uniper Group.

What is the Uniper Inner Source License?
-----------------------------------

The Uniper Inner Source License (Uniper-ISL) is a software license under which software can be freely used and developed within the Uniper Group and the source code is available to all software developers within the Uniper Group. It thus enables collaborative development and business models similar to known open source models within the group without the risk of these becoming public outside Uniper.

The Uniper-ISL is based on a license of the so-called "copyleft" type, which not only ensures that source code is available and can be freely used, but that modifications and further developments must be made available under the same conditions so that the greatest possible benefit can be derived from the shared and developed code.

The license is available as an option for internal software development and can also be used in the context of orders and contracts between different parts of the Group.

In addition to the legal framework for sharing code within an open source-like development model, the Uniper ISL also provides the basis for adapting elements of the open source culture where they can help improve communication and collaboration and make processes more efficient, transparent and self-organized.

# Rights and obligations of the Uniper Inner Source License.

The Uniper-ISL maps rights and obligations known from open source licenses to the scenario of intra-group development.

It is important to note that the rights and freedoms arising therefrom are always limited to use and disclosure within the group. Any transfer to parties outside the group requires explicit re-licensing, which must be carried out by the relevant rights holders.

Software licensed under the Uniper-ISL complies with the four freedoms of open source software within the group:

1. the software can be used within the group without restrictions

2. the source code of the software is available to all users

3. users can modify the software independently in order to make adjustments and improvements

4. modified versions of the software can be passed on to others

Freedoms are exercised solely on the basis of the license. No license payments or other additional agreements are required.

If there are requirements that go beyond the rights granted by the license, for example regarding liability and warranty or additional guarantees for support or development, additional agreements covering these requirements are necessary. The Uniper-ISL therefore permits such agreements to be entered into.

The main obligation of the Uniper-ISL is to make the source code of the software licensed under the Uniper-ISL available to all recipients of the software. This includes the original code as well as any modifications that have been made to the code.

This obligation cannot be limited, and thus propagates from one recipient of the software to the next. This ensures that the effort that goes into developing the software is available to the widest possible group of recipients. Any further developments thus also benefit all other users of the software, in the sense of optimization for the Uniper Group.

The Uniper-ISL generally permits so-called "forks", i.e. development branches of the software that are continued independently of the original branch. However, this should only be necessary in well-founded exceptional cases. In any case, it is advisable to develop together on one branch and to make changes in the main branch, or at least to let them flow back in a timely manner. This avoids the expense of parallel developments, leads to optimal value creation by bundling development capacities, and ensures that the software can be maintained sustainably.

# Application scenarios

The use of the Uniper-ISL is appropriate whenever code is to be made available to a broad audience within the Uniper Group in a way that is as easy to use as possible and collaboration on this code is to be enabled and encouraged.

In principle, the Inner Source model can be used for a variety of use cases. It is particularly suitable for the following cases:

- Infrastructure and tools that are similar for many projects, and usually do not represent the technical core of the application.

- Reference implementations, which are to be made available as simply as possible to as large an audience as possible

- Customer orders, in which the customer expects the software to be as widely usable as possible

- Implementations of standards that help to establish generally accepted standards

The Uniper-ISL is not suitable for code that is developed under the business model of selling software usage licenses and for software that is to be distributed to recipients outside the Uniper Group. Here, depending on the use case, traditional proprietary or open source licenses are suitable.

# How is the Uniper Inner Source license applied?

The application of the license is done in a similar way as known from the Apache license.

An important principle is that existing license and copyright notices may not be removed, but must be preserved in their entirety when the software is distributed or modified. This ensures that there is clarity about the license and copyright holder of all parts of the software.

The license text is stored in a file with the name "LICENSE" (if necessary with a file extension like .TXT or .MD) in the root directory of the code repository. This file must always be included when the software is distributed, this applies to both distribution as source code and distribution in binary form.

If the software is distributed in binary form, an effective notice must be included as to how the recipient can obtain the source code from which the binary form was generated.

Ideally, all code developed under the Uniper-ISL is maintained in a version control system that is equally accessible to all to make use of the code and collaboration on it as effective as possible.

In each file of source code, a reference to the license and the owner of the exploitation rights must be included at the beginning.

Example:

    // Copyright 2022 Uniper SE
    // Licensed under the Uniper-ISL, see the accompanying file LICENSE.

If changes are made to a file by a rights holder who is not yet named in the copyright notice, this new rights holder will insert an additional copyright line.

The years mentioned in the copyright notice should correspond to the years in which changes were made by the corresponding copyright holder. This can also be a list or range of years, for example "2019, 2021" or "2019-2020".

Material
--------

**Inner Source**

-   [How Inner Source is like FLOSSing](https://www.oreilly.com/ideas/how-innersource-is-like-flossing) - short lecture video explaining what Inner Source is and why it is good

-   [InnerSource Commons](https://innersourcecommons.org/) - Community resources from the field about Inner Source

-   [Adopting Inner Source, Principles and Case Studies](https://innersourcecommons.org/resources/books/adoptinginnersource/) - book with case studies of successful use of Inner Source in companies like Bosch, Ericsson or Paypal

**Open Source Licenses**

For comparison here are the links to some other licenses:

-   [EUPL](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32017D0863) - EU open source license, adapted to the European legal situation, template for part of the Uniper-ISL.

-   [Kommentar EUPL](https://joinup.ec.europa.eu/sites/default/files/inline-files/EUPL-V11Broschuere-20090423WEB.pdf) - commented version of the EUPL

-   [LGPL](https://www.gnu.de/documents/lgpl-3.0.de.html) - Open-Source-License with "weak Copyleft"

-   [Apache Lizenz](https://www.apache.org/licenses/LICENSE-2.0) - one of the most common "permissive" licenses
