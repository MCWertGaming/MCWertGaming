```cpp
#include <iostream>
#include <string>

namespace Profile {
    std::string welcome() {
        return "Welcome to my profile!\n"
               "I'm Damon and specializing in"
               "Backend- + Desktop- + Game-development\n";
    }
    std::string skills() {
        return "My skills:\n"
               // programming languages
               "C++, GO, C, Java, Javascript, Typescript\n"
               // Frameworks
               "GTest, Gin\n"
               // Markup languages
               "Markdown, HTML, CSS\n"
               // DevOps
               "Docker, Docker-compose, PostgreSQL, Kubernetes, SQl, MongoDB\n";
    }
    std::string projects() {
        return "Projects I work on:"
               "CPP-Terminal - A TUI library for the modern terminal: https://github.com/jupyter-xeus/cpp-terminal\n"
               "Snek - A simple snake game for the terminal: https://github.com/BlackVyperStudios/snek\n"
               "Puroto - Next generation social media for furries: https://puroto.net\n"
               "MyFursona - A place for animals to live together: https://myfursona.art\n";
    }
    std::string social() {
        return "Find me here:"
               "Twitter: @staxthefox\n" "Github: @MCWertGaming\n" "Steam: @MCWertGaming\n"
               "Blog: openfoxblog.leven.dev\n" "Website: damon.leven.dev\n";
    }
}
int main() {
    std::cout << Profile::welcome() << Profile::skills() << Profile::projects() << Profile::social();
    return 0;
}
```