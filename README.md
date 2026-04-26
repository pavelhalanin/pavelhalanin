## 1. Full Name

Pavel Halanin

<img src="https://pavelhalanin.github.io/RSSchool_2026Q1_Stage0__CV/assets/favicon/favicon_144.png" />

Middle Software Engineer

Work Experience 3 year

(JavaScript, React, React Native, Next.js, Node.js, NestJS, PHP, REST API, SwaggerUI, Docker, Git)

## 2. Contact information

- **Phone**: [+375-33-331-32-03](tel:+375333313203)
- **E-mail**: [pavelhalanin@outlook.com](mailto:pavelhalanin@outlook.com)
- **Discord**: [pavgal](https://discord.com/users/1482615972060991488)
- **GitHub**: [pavelhalanin](https://github.com/pavelhalanin)
- **LinkedIn**: [pavelhalanin](https://www.linkedin.com/in/pavelhalanin/)
- **CodeWars**: [rsschool](https://www.codewars.com/users/rsschool_7f3e087f4b5570c1)
- **WebSite**:
    - [OOO DE-PA](https://www.de-pa.by/)
    - [Kung Consulting](https://www.kungconsulting.com/)

## 3. Brief Self-Introduction

Software Engineer with 3 years of commercial experience, graduated with honors in Software Engineering. Began my career at DE-PA, then joined ATLANT, where I was promoted to Software Engineer 2nd Category within two years. Tech stack: JavaScript, React, React Native, Next.js, Node.js, NestJS, PHP, REST API, SwaggerUI, Docker, Git. Seeking a Middle Software Engineer position in a professional team with opportunities for further growth.

## 4. Skills

- programming languages: JavaScript, PHP8, SQL, TypeScript
- frameworks: React, ReactNative, NextJS, NestJS
- methodologies: ARIS, UML
- version control systems: Git, SVN
- IDE: VS Code
- Package Managers: npm, yarn
- Debugging Tools: Chrome DevTools
- Operating Systems: Windows, Linux
- API Testing: Postman, SwaggerUI
- Markup & Documentation Languages: HTML5, CSS3, MarkDown, LaTeX, JSON
- Databases: MySQL, Oracle, SQLite, DBF
- Containers & Virtualization: Docker, docker-compose
- Design: Figma, Photopea, Adobe Photoshop
- Hosting & Server Management: cPanel, ISPmanager, Hoster.by, Login.by
- AI & Local Models: Ollama
- DevOps & Infrastructure: Apache, WAMP, nginx

## 5. Code Examples

```js
function getCardId(value) {
    const ARRAY_RANK = ['A', '2', '3', '4', '5', '6', '7', '8', '9', '10', 'J', 'Q', 'K'];
    const ARRAY_SUIT = ['♣', '♦', '♥', '♠'];
    const RANK = `${value}`.replace(/[♣♦♥♠]$/, '');
    const SUIT = `${value}`.replace(/[^♣♦♥♠]/g, '');
    const RANK_ID = ARRAY_RANK.indexOf(RANK);
    const SUIT_ID = ARRAY_SUIT.indexOf(SUIT);
    return RANK_ID + 13 * SUIT_ID;
}
```

```js
class Helper {
    static async fetchCompanyData_byUnp(unp) {
        const URL_ = `https://grp.nalog.gov.by/api/grp-public/data?unp=${unp}`;
        const RESPONSE = await fetch(URL_);

        const HTTP_STATUS = RESPONSE.status;
        if (HTTP_STATUS !== 200) {
            const TEXT = await RESPONSE.text();
            throw new Error(`HttpStatus ${HTTP_STATUS}\n${TEXT}`);
        }

        const DATA = await RESPONSE.json();
        return DATA;
    }
}

try {
    const DATA = Helper.fetchCompanyData_byUnp(100582333);
    console.log(DATA);
}
catch(exception) {
    console.error(exception);
}
```

## 6. Work Experience (3 year)

- ZAO ATLANT (June 2024 - present) (2 year)
    - 2nd category Software Engineer (December 2025 - present)
    - Software Engineer (June 2024 - December 2025)

- OOO DE-PA (1 year)
    - Software Engineer (June 2023 - June 2024)

## 7. Education

- Tech education
    - Brest State Technical University (4 years)
        - September 2019 - June 2023 
        - Diploma of Higher Education with Honors
        - Qualification: "Software Engineer"
        - Specialty: "Information Technology Software"
- Driving licence
    - Category C
    - Category B, Am
 - Courses
    - RS School Stage 0 (16 March 2026 - 01 June 2026)
        <table>
            <thead>
                <tr>
                    <th>Task/Event</th>
                    <th>Type</th>
                    <th>Start Date</th>
                    <th>End Date</th>
                    <th>Repo</th>
                    <th>Web</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Git test (EN)</td>
                    <td>Test</td>
                    <td>16.03.2026</td>
                    <td>11.05.2026</td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td>CV#1. Markdown & Git</td>
                    <td>Coding</td>
                    <td>16.03.2026</td>
                    <td>30.05.2026</td>
                    <td>
                        <a href="https://github.com/pavelhalanin/RSSchool_2026Q1_Stage0__CV">repo</a>
                    </td>
                    <td>
                        <a href="https://pavelhalanin.github.io/RSSchool_2026Q1_Stage0__CV/cv">web</a>
                    </td>
                </tr>
                <tr>
                    <td>[St1] Test HTML Basics</td>
                    <td>Test</td>
                    <td>23.03.2026</td>
                    <td>11.05.2026</td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td>[St1] Test CSS Basics</td>
                    <td>Test</td>
                    <td>23.03.2026</td>
                    <td>11.05.2026</td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td>CV#2. HTML, CSS & Git Basics</td>
                    <td>Coding</td>
                    <td>23.03.2026</td>
                    <td>30.03.2026</td>
                    <td rowspan="3">
                        <a href="https://github.com/pavelhalanin/RSSchool_2026Q1_Stage0__CV">repo</a>
                    </td>
                    <td rowspan="3">
                        <a href="https://pavelhalanin.github.io/RSSchool_2026Q1_Stage0__CV/">web</a>
                    </td>
                </tr>
                <tr>
                    <td>CV#3. CV. Cross Check</td>
                    <td>Cross-Check: Submit</td>
                    <td>23.03.2026</td>
                    <td>30.03.2026</td>
                </tr>
                <tr>
                    <td>CV#3. CV. Cross Check</td>
                    <td>Cross-Check: Review</td>
                    <td>30.03.2026</td>
                    <td>03.04.2026</td>
                </tr>
                <tr>
                    <td>Codewars Part 1</td>
                    <td>Coding</td>
                    <td>30.03.2026</td>
                    <td>27.04.2026</td>
                    <td></td>
                    <td>
                        <a href="https://www.codewars.com/users/rsschool_7f3e087f4b5570c1">CodeWars</a>
                    </td>
                </tr>
                <tr>
                    <td>[St1] JS Basics</td>
                    <td>Test</td>
                    <td>06.04.2026</td>
                    <td>11.05.2026</td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td>Human Readable Number</td>
                    <td>Coding</td>
                    <td>06.04.2026</td>
                    <td>11.05.2026</td>
                    <td>
                        <a href="https://github.com/pavelhalanin/human-readable-number">repo</a>
                    </td>
                    <td></td>
                </tr>
                <tr>
                    <td>Reverse Int</td>
                    <td>Coding</td>
                    <td>06.04.2026</td>
                    <td>11.05.2026</td>
                    <td>
                        <a href="https://github.com/pavelhalanin/reverse-int">repo</a>
                    </td>
                    <td></td>
                </tr>
                <tr>
                    <td>Codewars Part 2</td>
                    <td>Coding</td>
                    <td>06.04.2026</td>
                    <td>27.04.2026</td>
                    <td></td>
                    <td>
                        <a href="https://www.codewars.com/users/rsschool_7f3e087f4b5570c1">CodeWars</a>
                    </td>
                </tr>
                <tr>
                    <td>Christmas shop. Part 1: Fixed Layout [EN]</td>
                    <td>Cross-Check: Submit</td>
                    <td>03.30.2026</td>
                    <td>06.04.2026</td>
                    <td rowspan="6">
                        <a href="https://github.com/pavelhalanin/RSSchool_2026Q1_Stage0__ChristmasShop">repo</a>
                    </td>
                    <td rowspan="6">
                        <a href="https://pavelhalanin.github.io/RSSchool_2026Q1_Stage0__ChristmasShop/christmas-shop/">web</a>
                    </td>
                </tr>
                <tr>
                    <td>Christmas shop. Part 1: Fixed Layout [EN]</td>
                    <td>Cross-Check: Review</td>
                    <td>06.04.2026</td>
                    <td>10.04.2026</td>
                </tr>
                <tr>
                    <td>Christmas shop. Part 2: Responsive Design [EN]</td>
                    <td>Cross-Check: Submit</td>
                    <td>06.04.2026</td>
                    <td>13.04.2026</td>
                </tr>
                <tr>
                    <td>Christmas shop. Part 2: Responsive Design [EN]</td>
                    <td>Cross-Check: Review</td>
                    <td>13.04.2026</td>
                    <td>17.04.2026</td>
                </tr>
                <tr>
                    <td>Christmas shop. Part 3: Adding Functionality [EN]</td>
                    <td>Cross-Check: Submit</td>
                    <td>13.04.2026</td>
                    <td>20.04.2026</td>
                </tr>
                <tr>
                    <td>Christmas shop. Part 3: Adding Functionality [EN]</td>
                    <td>Cross-Check: Review</td>
                    <td>20.04.2026</td>
                    <td>24.04.2026</td>
                </tr>
                <tr>
                    <td>core-js-101(S0)</td>
                    <td>Coding</td>
                    <td>20.04.2026</td>
                    <td>11.05.2026</td>
                    <td>
                        <a href="https://github.com/pavelhalanin/core-js-101-stage0">repo</a>
                    </td>
                    <td></td>
                </tr>
                <tr>
                    <td>Dashboard Project</td>
                    <td>Cross-Check: Submit</td>
                    <td>20.04.2026</td>
                    <td>04.05.2026</td>
                    <td rowspan="2">
                        <a href="https://github.com/pavelhalanin/RSSchool_2026Q1_Stage0__ChristmasShop">repo</a>
                    </td>
                    <td rowspan="2">
                        <a href="https://pavelhalanin.github.io/RSSchool_2026Q1_Stage0__ChristmasShop/christmas-shop/">web</a>
                    </td>
                </tr>
                <tr>
                    <td>Dashboard Project</td>
                    <td>Cross-Check: Review</td>
                    <td>04.05.2026</td>
                    <td>08.05.2026</td>
                </tr>
            </tbody>
        </table>

## 8. English Language

### About English

I read, I speak fluently. I've been practicing English for 12 years.

### Other languages

- Russian - native Landuage
- Belarusian - native Landuage
