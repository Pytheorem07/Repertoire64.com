Repertoire64 - Chess Opening Trainer

Repertoire64 is a professional-grade, web-based chess utility designed to help players build, study, and train their opening repertoires. Whether you are a beginner looking to learn the basics or a competitive player sharpening your lines, this tool provides the environment you need to master your moves.

This project is built as a single-file, portable application, making it incredibly easy to host or run locally.

✨ Key Features

Repertoire Building: Create and organize multiple repertoires. Add custom notes, comments, and variation names to specific positions.

Smart Training Mode: Practice your lines with auto-play or manual input. Features a "Smart Skip" mode that remembers lines you've already mastered to focus your time on difficult deviations.

Engine & Database Integration:

Stockfish Analysis: Integrated engine for depth-based evaluation.

ChessDB Access: Query master games directly within the interface to see popular and statistically successful moves.

Mistake Review: Automatically tracks errors made during training sessions and provides a dedicated "Review" mode to revisit and correct those mistakes.

Customization: Fully configurable board themes, piece styles, and visual aids (legal move dots, evaluation bars).

Portable: Everything is contained within a single HTML file—just open it in your browser to start studying.

🛠️ Technology Stack

Frontend: HTML5, Tailwind CSS for a sleek, dark-mode responsive interface.

Chess Logic: Chess.js for move validation and game state management.

Analysis: Stockfish.js for real-time engine evaluation.

Audio: Tone.js for high-quality, responsive board sound effects.

Storage: LocalStorage for persistent repertoire and settings management.

🚀 How to Use

Run: Open the index.html file in any modern web browser.

Build: Navigate to the "Build" tab to create your first repertoire and start adding lines.

Train: Move to the "Train" tab to test your recall of the lines you have built.

Analyze: Use the "Explore" view to analyze positions against the engine and master database.

Backup: Use the "Import/Export" buttons in the Build tab to save your work as a JSON file or restore your repertoires on another computer.

📦 Local Setup

Since this is a single-file project, no complex build process is required:

Clone this repository.

Simply double-click the index.html file to open it in your browser.

Note: If you are hosting this on a web server, ensure your server supports standard file serving.

🤝 Contributing

Contributions are welcome! If you have suggestions for new features, themes, or engine improvements, feel free to submit a pull request or open an issue.

📄 License

This project is open-source and available for personal or educational use.
