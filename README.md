# Design Rules
Design rules serve as guidelines to maintain consistency and coherence throughout the visual elements of the design system.

# h1
The `h1` tag serves as the main header, typically used for the primary title of a page or section. It often carries the most visual weight and sets the tone for the content that follows.

# h2
The `h2` tag functions as a sub-header, providing a level of hierarchy below the main header. It's commonly used for section titles or subsections within a page.

# p
The `p` tag represents paragraphs of text, serving as the standard text element. It's used for body content, descriptions, and other narrative elements.

# Card
![Card](https://i.imgur.com/I5cPhs3.png)

The `card` tag is a structured container that typically displays two lines of text, consisting of an `h1` and `h2` element.
> **Note:** paragraphs (`p` tags) are not supported within cards.

### Code Example
    <div  class="card">
		<div  class="band"></div>
		<h1>Main Text</h1>
		<h2>Sub Text</h2>
	</div>

> **Note:** The div with the class band is not required. If the band div is not there the text will automatically recenter itself

# Button
![Button](https://i.imgur.com/j3PnYu3.png) ![Button](https://i.imgur.com/c9eNpjz.png) ![Button](https://i.imgur.com/AQeRTyh.png)

The `button` tag is a versatile element used for interactive controls, such as submitting forms, triggering events, or navigating between pages. It typically accommodates short text labels or icons.

# Small Button

![Small Button](https://i.imgur.com/4FePWBo.png)

Small buttons are similar to regular buttons but are optimized for compact spaces or secondary actions. They're commonly used for navigation elements, confirmation prompts, or adjusting settings.
