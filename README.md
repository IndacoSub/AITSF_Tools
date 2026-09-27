# AITSF_Tools

Tools used to create the Microsoft Store port of the unofficial AI: The Somnium Files 🇮🇹 translation by Team DAIX, Team Junes and Crash Keys Team.

> **AI-assisted development**
>
> Parts of this repository were developed with assistance from generative AI. AI was used during implementation, debugging, diagnostic analysis, Unity serialization research, and development of supporting tooling. The generated code was reviewed, adapted, and tested against the actual target files and game environment.

## Usage

1. Rename one of the TXTs to script_base.txt

2. Rename the corresponding .py to script.py

3. Edit the paths at the top of script.py to reflect yours (yes, you'll need a NewUAFGJ executable)

4. Run `python script_gui.py`

5. Select the stuff you'd like to compile, then click on "Generate script.py"

6. At that point you can either click on "Run BUILD.bat", or (recommended) manually run BUILD.bat (which just calls `python script.py` at this time) from the command-line.

Furthermore, unless you comment-out the copy_file line(s) in the script.py(s), you'll also need to provide a luabytecode with the text already imported through TranslationFramework2.

## Notes

As you can see from the script TXT files, font-importing has been disabled due to weird issues in-game, perhaps caused by NewUAFGJ.

As such, both script TXTs do not support it, and not just the new Microsoft Store port.

Working edited fonts are still present in the previous release of the Steam version, which was made manually and without automation (NewUAFGJ / UAFGJ).

If you're able to figure out the issue(s) and fix it, by all means feel free to open a Pull Request on the NewUAFGJ repository.

## License

This repository is licensed under the ISC License.

## Legal

This project is intended for research, preservation, interoperability, and modding purposes.

Do not redistribute copyrighted game assets unless you have the necessary rights or permission.

The repository does not include the game's proprietary resources.

	 "AI: THE SOMNIUM FILES" is a registered trademark of Spike Chunsoft Co., Ltd.