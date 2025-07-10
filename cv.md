# **Maksim Zhidkov**
## **Beginner Frontend Developer**

<img src="/assets/img/image-round.png" width="100" alt="My avatar" />

## Contacts

- **Phone:** +7 906 183-50-01
- **Email:** vjmax793@gmail.com
- **GitHub:** [Orgris](https://github.com/Orgris) 
- **Telegram:** [@orgris4](https://t.me/orgris4)
- **Discord:** Maksim (@orgris)

## Summary
Beginner frontend developer with a strong focus on learning and growth. Disciplined, deadline-oriented, and quick to adapt. Comfortable working in Agile teams and learning from existing codebases. Enjoy solving problems and exploring new tools and technologies. Comfortable communicating in English.

## Skills
- JavaScript
- HTML / CSS
- TypeScript
- Next.js
- Redux
- Chakra UI
- GitHub
- Notion
- Figma
- Firebase
- Vibe coding

## Code example

### Make the Deadfish Swim

Create a parser to interpret and execute the Deadfish language.
Deadfish operates on a single value in memory, which is initially set to 0.
It uses four single-character commands:
- i: Increment the value
- d: Decrement the value
- s: Square the value
- o: Output the value to a result array

All other instructions are no-ops and have no effect.

### Solution
    function parse(data) {
      let value = 0
      const result = []
      
      for (char of data.slice()) {
        switch (char) {
            case "i": value++; break;
            case "d": value--; break;
            case "s": value *= value; break;
            case "o": result.push(value); break;
            default: break;
        }
      }
      return result
    }

## Projects
### Information subsystem for managing educational tasks. Admin module
2024 - 2025 Master’s thesis project, web-based subsystem:
 - Built the admin module of a web-based subsystem to monitor and analyze the academic progress of over 500 university students across multiple courses;
 - Improved admin module usability by 30% through enhanced visual design and a carefully crafted color scheme using Chakra UI, creating a more intuitive and appealing interface;
 - Enabled efficient management of over 100 courses by integrating a rich text editor for creation and editing of educational materials.

### Children's location monitoring mobile application
2022 - 2023 Bachelor’s thesis project, native mobile application:
 - Utilized Java 8 to design and develop child healthcare native mobile application for Android as a bachelors work;
 - Designed a unified interface for parents and children with role-based PIN code access;
 - Integrated Google Maps API for live location display up to 10 children simultaneously and Firebase Realtime Database for cloud syncing.

## Experience
### Internship Program – Web Developer
02/2023 - 05/2023 ПНТЦ LLC Taganrog, Russia
- Achievements:
  - Improved delivery consistency by reducing task delays by 25% in a small Agile/Scrum team through proactive communication, realistic sprint planning, and refining user stories;
  - Identified 5 key IT trends that enriched the academic and practical foundation of the thesis project by analyzing over 30 international patents using RSCI, Dimensions, and Patentscope;
  - Delivered a functional prototype of a сhildren's location monitoring mobile app by aligning internship goals with master’s thesis objectives.

## Education
### Master’s Degree in Development of Information Systems and Web Applications (Red diploma)
- 09/2023 - 06/2025 Southern Federal University Taganrog, Russia
  - Web Application Development;
  - Ergonomics and Interface Design of Information Systems and Web Applications;
  - Methods and Tools for Designing Information Systems and Web Applications.

### Bachelor’s Degree in Advanced Information Technologies
- 09/2019 - 06/2023 Southern Federal University Taganrog, Russia
  - Technologies of Data Analysis and Visualization;
  - Multimedia Technologies;
  - Distance Information Technologies.

## Languages
- Russian - Native
- English - Intermediate