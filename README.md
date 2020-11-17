Tests for [microsoft/vscode#110830](https://github.com/microsoft/vscode/pull/110830).

# To Test

1. Clone this repo.
2. Install [the VSIX package](https://github.com/SPGoding/vscode-icon-theme-extender-tester/releases/tag/1.0.0) in Code - OSS Dev.
3. Switch through different icon themes:
    - `None`: no icons should be shown.  
    ![image](https://user-images.githubusercontent.com/15277496/99462748-f65a1a80-28f9-11eb-8b5b-7165c7c2a971.png)
    - `Minimal (Visual Studio Code)`: only built-in minimal icons should be shown.  
    ![image](https://user-images.githubusercontent.com/15277496/99462790-08d45400-28fa-11eb-9270-3df746f00782.png)
    - `Non-Extender` (an icon theme contributed by the test extension): Custom red icons should be shown for test.conflict. Custom green icons should be shown for test.general and test.non-extender. Default icon should be shown for test.vs-seti.  
    ![image](https://user-images.githubusercontent.com/15277496/99462817-138ee900-28fa-11eb-8a4d-528d666b3c76.png)
    - `Seti (Visual Studio Code)`: custom green icons should be shown for test.conflict, test.general, and test.vs-seti.
    ![image](https://user-images.githubusercontent.com/15277496/99462832-1c7fba80-28fa-11eb-8097-152c1f38da84.png)
