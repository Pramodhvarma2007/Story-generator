# Story Generator

A simple AI-powered story generator built in Google Colab using the Google Gemini API. Give it a topic, a genre and an approximate length, and it writes a short story for you.

**Author:** A. Pramodh Varma
**GitHub:** [Pramodhvarma2007](https://github.com/Pramodhvarma2007)

---

## Features

- Takes three inputs from the user: story topic, genre and approximate length (in words)
- Builds a prompt from those inputs and sends it to Gemini
- Prints the generated story directly in the notebook

## Tech Stack

- Python
- Google Colab
- Google Gemini API (`google-genai` library)

## Installation

Run this in the first cell of the notebook:

```python
!pip install -q -U google-genai
```

## Setup

1. Get a free API key from [Google AI Studio](https://aistudio.google.com/).
2. Add it to the notebook as `GEMINI_API_KEY`. In Colab, use **Secrets** (the key icon on the left sidebar).
3. Do **not** paste your API key directly into the code or upload it to GitHub.

## How to Run

1. Open `Story_generator.ipynb` in Google Colab.
2. Run the install cell.
3. Run all cells (**Runtime → Run all**).
4. Enter the story topic, genre and length when prompted.
5. The story is printed in the output.

## Example Run

**Inputs**

```
Enter story topic: A student who discovers a hidden library
Enter story genre: Mystery
Enter approximate story length: 300
```

**Output (excerpt)**

```
===== GENERATED STORY =====

The old university library was a labyrinth of mahogany shelves and whispered
secrets, but Elara always felt the architecture was hiding something.

Heart hammering, Elara stepped inside. The air grew cold, smelling of ozone
and ancient parchment. As she descended, her phone's flashlight cut through
the dark.

It wasn't just a room; it was a library of lost things.

Rows of shelves stretched into the gloom, packed with books bound in
iridescent scales, silver mesh, and strange, pulsating velvet. In the center
...

She froze. The clock on her phone read 11:41 PM.

Suddenly, the heavy door at the top of the stairs slammed shut with a
finality that shook the floorboards. The lights in the hidden room flickered.

From the shadows behind the desk, a voice rasped, calm and impossibly old.
"You're right on time, Elara. We've been expecting a new librarian for ..."

Elara spun around, ...
```

*(Output shortened here. Run the notebook to see the full story.)*

## Project Structure

```
story-generator/
├── Story_generator.ipynb   # Main notebook
└── README.md               # Project description
```

## Future Improvements

- Add a simple web interface
- Let the user choose tone or target audience
- Save generated stories to a file

## License

This project is for educational purposes.
