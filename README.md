```
namespace MikhailRamirez {

    class AboutMe {
    public:
        std::string getCurrentWorkplace() {
            return "Company: Outpost Technologies, Position: Software Analyst";
        }

        std::string otherProfiles() {
            return "Leetcode: https://leetcode.com/u/Mikhail_Ramirez/,
                    LinkedIn: www.linkedin.com/in/mikhail-ramirez-a569791aa;
        }

        std::vector<std::string> getDailyKnowledge() {
            return {
                "C++/C",
                "Python",
                "MATLAB",
                "Linux",
                "Embedded Systems"
            };
        }

        std::string getFutureGoal() {
            return "To learn everything!";
        }
    };

}
```
