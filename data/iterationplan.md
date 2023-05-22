This plan captures our work in **May**. This is a 4-week iteration. We will ship in **early June**.

## Endgame
- **May 22, 2023**: Endgame begins
- **May 26, 2023**: Endgame done


The endgame details for this iteration are tracked [here](https://github.com/microsoft/vscode/issues?q=is%3Aissue+label%3Aendgame-plan+milestone%3A%22May+2023%22).

## Plan Items

Below is a summary of the top level plan items.

Legend of annotations:

| Mark                 | Description                                       |
| -------------------- | ------------------------------------------------- |
| :runner:             | work in progress                                  |
| :hand:               | blocked task                                      |
| :muscle:             | stretch goal for this iteration                   |
| :red_circle:         | missing issue reference                           |
| :large_blue_circle:  | more investigation required to remove uncertainty |
| :black_circle:       | under discussion within the team                  |
| :black_large_square: | a large work item, larger than one iteration      |


### Accessibility
- [ ] Notebook output accessibility [vscode#178630](https://github.com/microsoft/vscode/issues/178630) @amunger
- [ ] :red_circle: Explore merge editor accessibility improvements @meganrogge @hediet
- [ ] Add more `accessibility.verbosity` settings / hints [vscode#180470](https://github.com/microsoft/vscode/issues/180470) @meganrogge
- [ ] Present content first in References tree view [vscode#180653](https://github.com/microsoft/vscode/issues/180653) @meganrogge
- [ ] Settings Editor value descriptions are not read by screen readers [vscode#180115](https://github.com/microsoft/vscode/issues/180115) @rzhao271
- [ ] :runner: Accessibility issues, see [query](https://github.com/Microsoft/vscode/issues?q=is%3Aopen+is%3Aissue+label%3Aaccessibility+milestone%3A%22May+2023%22) @meganrogge **team**


### UX
- None.

### Workbench
- [ ] :runner: Support Dev Containers and WSL in new Connect to... experience on Welcome Page [vscode-remote-release#8251](https://github.com/microsoft/vscode-remote-release/issues/8251) @bhavyaus @aeschli @chrmarti
- [ ] Show existing tunnels on Welcome page in vscode.dev [vscode#179687](https://github.com/microsoft/vscode/issues/179687) @bhavyaus @aeschli @connor4312
- [ ] Support experimental contextual non-modal dialogs to educate users on web experiences [vscode#179401](https://github.com/microsoft/vscode/issues/179401) @bhavyaus @joyceerhl @daviddossett
- [ ] :runner: Improve the keybinding recording widget [vscode#178042](https://github.com/microsoft/vscode/issues/178042) [vscode#179015](https://github.com/microsoft/vscode/issues/179015) [vscode#179018](https://github.com/microsoft/vscode/issues/179018) @ulugbekna
- [ ] :runner: Explore support for multiple GitHub accounts [vscode#127967](https://github.com/microsoft/vscode/issues/127967) @tylerleonhardt
- [ ] UX to alert users of a slow remote connection [vscode#178553](https://github.com/microsoft/vscode/issues/178553) @bpasero
- [ ] :runner: Support roaming workspace state via `StorageScope.WORKSPACE` and `StorageTarget.USER` in `IStorageService` [vscode#179898](https://github.com/microsoft/vscode/issues/179898) @joyceerhl @bpasero
- [ ] Support deduplicating SSH and HTTP remotes when computing edit session identities [vscode#180582](https://github.com/microsoft/vscode/issues/180582) @joyceerhl
- [ ] :runner: Add read-only mode [vscode#4873](https://github.com/microsoft/vscode/issues/4873) @bpasero
- [ ] Exploration: Allow Default profile to be a fallback for settings, extensions and keyboard shortcuts [vscode#156144](https://github.com/microsoft/vscode/issues/156144) @sandy081
- [ ] Adopt new extension host restart lifecycle [vscode#180514](https://github.com/microsoft/vscode/issues/180514) @sandy081 @lszomoru @rebornix @mjbvz @bpasero
- [ ] Drop support for windows 8 and 8.1 [vscode#177676](https://github.com/microsoft/vscode/issues/177676) @deepak1556


### Code Editor
- [ ] :muscle: Collapse unchanged regions in diff [vscode#3562](https://github.com/microsoft/vscode/issues/3562) @hediet
- [ ] :runner: Explore detecting moves in the diff editor [vscode#181902](https://github.com/microsoft/vscode/issues/181902) @hediet
- [x] Monaco Editor Release [0.38.0](https://github.com/microsoft/monaco-editor/blob/main/CHANGELOG.md#0380) @hediet


### Notebook Editor
- [ ] Support scrollable outputs for streaming text [vscode#177721](https://github.com/microsoft/vscode/issues/177721) @amunger @rebornix @mjbvz
- [ ] Align closing behavior of the Interactive Window with Untitled Files [vscode#172974](https://github.com/microsoft/vscode/issues/172974) @amunger
- [ ] Allow scrapbook untitled working copies [vscode#174485](https://github.com/microsoft/vscode/issues/174485) @amunger @bpasero
- [ ] :runner: Support `notebook.codeActionsOnSave` [vscode#179213](https://github.com/microsoft/vscode/issues/179213) @yoyokrazy
- [ ] Explore "Format Cell on Run" [vscode-jupyter#7058](https://github.com/microsoft/vscode-jupyter/issues/7058) @Yoyokrazy
- [ ] :red_circle: Explore Sticky Scroll showing markdown headers in notebooks @Yoyokrazy
- [ ] Polish global search options for open notebooks [vscode#164926](https://github.com/microsoft/vscode/issues/164926) @andreamah
- [ ] Explore smart global search for notebooks in the workspace [vscode#173726](https://github.com/microsoft/vscode/issues/173726) @andreamah
- [ ] :runner: Static resources fail to load in Notebook renderer with 401 error [vscode#175033](https://github.com/microsoft/vscode/issues/175033) @mjbvz


#### Jupyter Notebooks
- [ ] :runner: Contributions to the vscode-jupyter extension [vscode-jupyter#13471](https://github.com/microsoft/vscode-jupyter/issues/13471) **team**


### WebAssembly Runtime Support
- [ ] Convert Python WASM-WASI extension to the new library extension [vscode-python-web-wasm#47](https://github.com/microsoft/vscode-python-web-wasm/issues/47) @dbaeumer
- [ ] :runner: Provide an extensible web-shell [vscode-wasm#63](https://github.com/microsoft/vscode-wasm/issues/63)@dbaeumer


### Languages

#### Python
- [ ] :runner: Contributions to the python extension [vscode-python#21196](https://github.com/microsoft/vscode-python/issues/21196) @brettcannon **team**

##### Python WebAssembly Runtime Support
- None.

#### JavaScript/TypeScript
- [ ] :runner: Automatic type acquisition on the web [vscode#172887](https://github.com/microsoft/vscode/issues/172887) @mjbvz
- [ ] :runner: Project-wide IntelliSense on the web [vscode#170920](https://github.com/microsoft/vscode/issues/170920) @mjbvz

#### Language Server Protocol
- [ ] :runner: Investigate to extract a base protocol definition out of the LS protocol [1707](https://github.com/microsoft/language-server-protocol/issues/1707) @dbaeumer


### Source Control
- [ ] :red_circle: Allow customizing initial branch when initializing a Git repository @lszomoru
- [ ] Handle GitHub's Secret Scanning Push Protection [vscode#169355](https://github.com/microsoft/vscode/issues/169355) @lszomoru
- [ ] :red_circle: Support GitHub Repository Rules as branch protections @lszomoru

### Terminal
- [ ] :runner: Make fixes to environment workspace collection and finalize proposed APIs [vscode#171108](https://github.com/microsoft/vscode/issues/171108) [vscode#181755](https://github.com/microsoft/vscode/issues/181755) @karrtikr
- [ ] :runner: Allow EnvironmentVariableCollection API to apply changes via shell integration [vscode#179476](https://github.com/microsoft/vscode/issues/179476) @tyriar @karrtikr


### Testing
- [ ] :muscle: Support for ANSI colors in test output [vscode#151964](https://github.com/microsoft/vscode/issues/151964) @connor4312
- [ ] :muscle: Start drafting a retired test item API [vscode#134970](https://github.com/microsoft/vscode/issues/134970) @connor4312


### vscode.dev
- [ ] Opening vscode.dev should not require a browser reload to update web extensions [vscode#174682](https://github.com/microsoft/vscode/issues/174682) @sandy081


### API
- [ ] :muscle: Explore `ShareableDataProvider` API [vscode#176316](https://github.com/microsoft/vscode/issues/176316) @joyceerhl
- [ ] :runner: Stabilize `DocumentPasteEditProvider` API to support pasting images [vscode#30066](https://github.com/microsoft/vscode/issues/30066) @mjbvz
- [ ] Explore static status bar contributions [vscode#167874](https://github.com/microsoft/vscode/issues/167874) @jrieken
- [ ] Finalize tree checkboxes API [vscode#116141](https://github.com/microsoft/vscode/issues/116141) @alexr00
- [ ] Finalize port attributes API [vscode#115616](https://github.com/microsoft/vscode/issues/115616) @alexr00
- [ ] :runner: API proposals: [query](https://github.com/Microsoft/vscode/issues?q=is%3Aissue+is%3Aopen+milestone%3A%22May+2023%22+label%3A%22api-proposal%22) @jrieken @mjbvz
- [ ] :runner: API finalization: [query](https:/github.com/Microsoft/vscode/issues?q=is%3Aissue+is%3Aopen+milestone%3A%22May+2023%22+label%3A%22api-finalization%22) @jrieken @mjbvz

### Extensions
- [ ] Adopt using platform specifier in path for web extensions [vscode#180525](https://github.com/microsoft/vscode/issues/180525) @sandy081


### Extension Contributions
- [ ] :runner: Improvements to the Remote extensions [vscode-remote-release#8455](https://github.com/microsoft/vscode-remote-release/issues/8455) @eleanorjboyd @chrmarti @aeschli @joyceerhl @connor4312
- [ ] Nudge users towards sign-in [vscode-pull-request-github#4756](https://github.com/microsoft/vscode-pull-request-github/issues/4756) @alexr00
- [ ] Allow checked-ed out PRs to show diffs only against PR head [vscode-pull-request-github#4720](https://github.com/microsoft/vscode-pull-request-github/issues/4720) @alexr00


### Engineering
- [ ] :red_circle: Roll out sandboxing to all users @digitarald
- [ ] :runner: Adopt utility process in terminal/pty host [vscode#175335](https://github.com/microsoft/vscode/issues/175335) @tyriar @bpasero
- [ ] :muscle: Improving the developer experience for the CLI within the vscode repo [vscode#171515](https://github.com/microsoft/vscode/issues/171515) @aeschli @connor4312


#### Electron
- [ ] Orca can't be stopped in native dialogs [vscode#121811](https://github.com/microsoft/vscode/issues/121811) @deepak1556
- [ ] Right Click acting abnormal [vscode#113175](https://github.com/microsoft/vscode/issues/113175) @deepak1556
- [ ] Code - OSS doesn't launch when using Dev Container locally or in codespaces [vscode#168655](https://github.com/microsoft/vscode/issues/168655) @deepak1556

----
### Deferred
- [ ] Support that servers can read from remote file systems [1264](https://github.com/microsoft/language-server-protocol/issues/1264) @rchiodo / @dbaeumer
- [ ] Explore prompting to enable Cloud Changes on save in web [vscode#179014](https://github.com/microsoft/vscode/issues/179014) @joyceerhl
- [ ] Explore alternative wording for "Continue On" explanations [vscode#180106](https://github.com/microsoft/vscode/issues/180106) @hbons
- [ ] :hand: Add elided text (editor core subset of [vscode#170447](https://github.com/microsoft/vscode/pull/170447)) @hediet @alexdima
- [ ] :hand: :black_large_square: PGO for VSCode Desktop [vscode#170931](https://github.com/microsoft/vscode/issues/170931) @deepak1556
- [ ] Walkthrough images load slowly [vscode#166890](https://github.com/microsoft/vscode/issues/166890) @bhavyaus
- [ ] :runner: Explore support for extensions to provide additional data to the issue reporter [vscode#46726](https://github.com/microsoft/vscode/issues/46726) @TylerLeonhardt
- [ ] :runner: Make editor hovers resizable [vscode#14165](https://github.com/microsoft/vscode/issues/14165) @aiday-mar
- [ ] :runner: Exploration: Re-think PR creation flow [vscode-pull-request-github#4403](https://github.com/microsoft/vscode-pull-request-github/issues/4403) @alexr00 @hbons
- [ ] Exploration: Cross-profile settings and extensions [vscode#176813](https://github.com/microsoft/vscode/issues/176813) [vscode#157492](https://github.com/microsoft/vscode/issues/157492)@sandy081
- [ ] :black_large_square: [vscode#179000](https://github.com/microsoft/vscode/issues/179000) Exploration: Changes editor @lszomoru
- [ ] :muscle: Surface Dependabot alerts in workbench [vscode#178991](https://github.com/microsoft/vscode/issues/178991) @lszomoru
