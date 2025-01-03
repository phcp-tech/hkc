English | [简体中文](./README-zh-hans.md)

# HKC: Human Knowledge Classification


HKC is a human-centered knowledge classification method defined by identifying the relationship between human and ego(Philosophy), human and gods(Religion), human and human(Society/Culture/Art), human and nature(Science/Technology).


## 1 Definition of knowledge

**Data**: Unprocessed information

**Information**: Derived by associating facts with a given context

**Knowledge**: Associating the information in a certain context with information obtained from different contexts

**Wisdom**: General principles derived from completely different knowledge.


## 2 Definition of HKC

Currently, different countries in the world use different book classification methods to classify books, such as the Dewey Decimal Classification DDC<sup>[1]</sup>, Universal Decimal Classification UDC<sup>[2]</sup> derived from DDC, the Library of Congress Classification LCC<sup>[3]</sup>, the Chinese Library Classification CLC<sup>[4]</sup>, etc. These methods have their own pros and cons. For example, the Dewey classification method has a long history, but it does not support the classification of emerging sciences and technologies enough. For example: computer science, such an important area but is only placed in the general category; The Library of Congress classification method assigns a large amount of numbering to books from Europe and America, reflecting the strong position of American culture in world culture but not paying enough attention to the culture of other regions; The Chinese library classification method appears to be quite ideological, etc. All of these have failed to meet the classification needs of books in the modern information society, which is not beneficial to roll them out. Therefore it is imperative to create a new classification method.

Based on UDC, we have created a new classification method, referred to as **HKC (Human Knowledge Classification)**, which is not only suitable for book classification, but also to meet the requirements of current information development, preparing for the future dissemination of human civilization.

The classification principle of HKC is human-centered, distinguishing the relationship between human and external objects, and classifying according to the relationship between human and themselves, human and gods, human and human, and human and nature:

**Relationship between human and ego**: one is the only person who is respected from heaven to earth. If one loses themself, the world will not exist and there will be no meaning for it. This category covers philosophy, epistemology, psychology, self-achievement, etc., which are purely individual experiences and feelings;

**Relationship between human and gods**: Considering the huge impact of religions on human society, and to not make too much changes to the original UDC classification method, a separate relationship was established, that is, the relationship between human and gods. A separate category was reserved for religion;

**Relationship between human and human**: growth up, one first comes into contact with parents and family, then schools, society, and nation. All these are intertwined with relationships between people. In fact, it is sociology;

**Relationship between human and nature**: This part of the content can be classified as natural science and technology.



## 3 HKC Classification

The specifics of the HKC classification method is as follows, generally following the UDC classification method, and some classifications have been adjusted. The latest and more detailed content will be promptly published on the HKC website, please see: https://hkc.wiki

HKC uses the following principles for sorting classifications: chronological order, causal relationship, level of importance.

### 3.1 H0: The relationship between human and ego

Sorted causally.

000: Philosophy

010: Metaphysics

020: Epistemology

030: Logic

040: Aesthetics

050: Ethics

060: Psychology

070: Vijnanavada: This is a new classification added to the philosophy category. Buddhist Vijnanavada has a huge and irreplaceable role in understanding the world and knowing oneself.

### 3.2 H1：The relationship between human and gods

Sorted chronologically in the order of religions' emergences.

110: Hinduism

120: Judaism

130: Buddhism

140: Christianity

150: Islam

160: Bahá'í

170: National Religion

[Note] According to HKC's definition of religion, the problem raised by Matteo Ricci, an Italian Catholic missionary who came to China in the 17th century, can be solved. That is, "Is Confucianism a religion?"<sup>[5]</sup>, which has caused many debates in the academic world. In fact, the answer is very direct and simple: Confucianism is not a religion since it focuses not on the relationship between human and gods, but on the relationship between human and human.


### 3.3 H2：The relationship between human and human

Sorted causally. This category occupies 3 major categories numbered 3/4/5, which are society/culture/art. The UDC cultural and artistic classification numbering are 8 and 7, which have been adjusted here.

**200：Society** 

Sorted in chronological order of contact between people.

210: Family

220: Society

230: Economy

240: Politics

250: Law

260: Nation

270: Globalization

280: Management


**300: Culture**

The UDC stipulates that this category is defined by each library themselves.

310: Education

320: Linguistics

330: History

340: Anthropology

350: National Culture

**400: Art**

Sorted in chronological order of emergence.

410: Music

420: Painting

430: Literature

440: Dance and Drama

450: Sculpture

460: Photography and Film

470: Games and Sports

480: National Art


### 3.4 H3: The relationship between human and nature

This category is divided into science and technology, and reserving a major category for future technologies.

**500 Science**

Sorted in both chronological order of emergence and causality.

510: Mathematics

520: Biology

530: Physics

540: Chemistry

550: Geology

560: Astronomy

**600 Technology**

Sorted in chronological order of emergence.

610: Medicine

620: Agriculture

630: Industry

640: Materials Science 

650: Architecture 

660: Transportation 

670: Energy 

680: Information and Communication 

690: Aerospace 


### 3.5 H4: The relationship between human and new civilizations

With the development of human technology, artificially created life forms and artificial intelligence life forms will appear. The civilizations developed by these two life forms will inevitably develop relations with humans. These two relationships cannot be included in any of the above relationships.

In addition, there is a kind of relationship-corresponding object in nature that is currently unknown to humans and it is uncertain whether it exists or not, that is, extraterrestrial life. This kind of relationship cannot be classified into any of the above categories: they are not humans and cannot be classified as human-to-human relationships; they are not gods, in a sense they are equal to humans, not gods who created humans, so they cannot be classified as human-to-god relationships; they are also not ruthless in nature, they are sentient beings but have different origins from humans, so they cannot be classified as human-to-nature relationships.

Based on these two reasons, a new kind of relationship was established: relationship between human and new civilization.

710: Futurology

720: Artificial Intelligence 

730: Artificial Life 

740: Solar Civilization 

750: Galactic Civilization

760: Cosmos Civilization

## 4 HKC numbering method

HKC uses dotted hexadecimal numbering to achieve maximum expansion.

The format is ABC.X.Y, with a total of 5 levels. The first three levels are hexadecimal values from 0-9, A-F, each level expressing up to 16 major categories; after this, it is separated by decimal points ".", and up to three levels of numbering can be set; the last two levels X/Y use sequential decimal numbers, and each level can be expanded to a maximum of 255. Therefore, the maximum code of this classification method is FFF.255.255, far exceeding the amount of classifications currently required by human knowledge.

- [ ] A: Represents Knowledge  **(System)**, for example, 0 represents philosophy, 1 represents religion, 6 represents technology, and the maximum can be represented as F, that is, 000, 100, 600, F00;

- [ ] B: Represents the industry under A's system **(Industry)**, for example, in the technology category 600, 8 represents the information and communication industry, that is, 680; the maximum can be represented as F, that is, 6F0;

- [ ] C: Represents the subject under B's industry **(Subject)**, for example, in the information and communication industry 680, 2 represents computer science, that is, 682; the maximum can be represented as F, that is, 68F;

- [ ] X: Represents the domain under C's subject **(Domain)**. For example, in computer science 682, 3 represents software engineering domain, that is, 682.3. The maximum value is 255;

- [ ] Y: Represents the subdomain under X's domain **(Subdomain)**. For example, in software engineering 682.3, 2 represents requirement analysis, that is, 682.3.2. The maximum value is 255;

Since each industry/domain has various amounts of knowledge classifications, only the first three levels are required in the numbering and the last two levels are optional. For example,"Judaism" is coded as 120. Historically Judaism has not had many branches and its teachings are relatively complete and unified so it has no XY levels.

The corresponding relationship of HKC coding architecture: 
![](https://ar-io.net/nVBgLKQZZzNL97fdrq5MIBfR0o-gEy8XA5URaFttSPM)


## 5 HKC Scope of Use

Due to its high expandability, HKC can not only classify traditional books in libraries, but also classify the numerous electronic publications in the information society, and is more suitable for classifying future human knowledge.


**Recommended reading**

[1] Introduction to Domain Knowledge: https://zhishi.io/resources/Introduction-to-Domain-Knowledge-2jElmrt

[2] Introduction to KCMM: https://zhishi.io/resources/Introduction-to-KCMM-Goo1waE


**References**

[1] DDC: https://en.wikipedia.org/wiki/Dewey_Decimal_Classification

[2] UDC: https://en.wikipedia.org/wiki/Universal_Decimal_Classification

[3] LCC: https://en.wikipedia.org/wiki/Library_of_Congress_Classification

[4] CLC:   
https://zh.wikipedia.org/wiki/%E4%B8%AD%E5%9B%BD%E5%9B%BE%E4%B9%A6%E9%A6%86%E5%88%86%E7%B1%BB%E6%B3%95

[5] Fang Zhaohui "Middle School" and "Western Learning": Reinterpreting Modern Chinese Academic History  https://www.aisixiang.com/data/50428.html
