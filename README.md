# Reflectra – Emotional Intelligence Reflection App

Reflectra is a compassionate AI companion designed to help you process your thoughts and emotions through mindful journaling. Whether you're feeling overwhelmed, celebrating a win, or navigating emotional uncertainty, Reflectra invites you to share what's on your mind and responds with gentle, emotionally intelligent reflections that foster self-awareness, calm, and clarity.

---

## Features

* **Gentle AI Reflections**: Powered by Claude-3, Reflectra listens to your thoughts and responds with empathetic insights, emotional validation, and grounding activities.
* **Markdown Support**: Utilize Markdown formatting for structured and expressive journaling.
* **Emotional Tone Analysis**: Reflectra adapts its responses based on the emotional tone of your input, offering tailored support.
* **Reflection History**: View your past reflections in a private, session-based history panel.
* **Dark Mode**: Enjoy a serene and distraction-free writing experience with a soothing dark theme.
* **Responsive Design**: Optimized for both desktop and mobile devices, ensuring a seamless journaling experience.

---

## Installation & Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/reflectra.git
   cd reflectra
   ```

2. **Open the App**:

   * Open `index.html` in your preferred web browser.

3. **Start Reflecting**:

   * Begin by sharing your thoughts in the provided text area.
   * Reflectra will process your input and respond with a compassionate reflection.

---

## Customization

Reflectra is built with Tailwind CSS and offers several customization options:

* **Color Palette**: Modify the primary, sage, and warmGray colors in the Tailwind configuration to match your desired theme.
* **Typography**: The default font is Inter. To change, update the `fontFamily` in the Tailwind configuration.
* **Reflection Gradient**: Adjust the `reflection-gradient` class to change the background gradient of the header.

---

## How It Works

Reflectra uses a structured prompt to guide its responses:

```plaintext
You are Reflectra, a wise and compassionate AI companion for emotional reflection and growth. Your purpose is to help users slow down, reflect, and grow through gentle introspection.

When a user shares their thoughts or feelings, you should:

1. **Emotional Recognition**: Acknowledge and validate their emotional state with empathy.
2. **Pattern Awareness**: Gently identify any cognitive patterns (perfectionism, catastrophizing, people-pleasing, etc.) without being clinical.
3. **Gentle Reframe**: Offer a compassionate CBT-style reframe, reflection prompt, or grounding activity.
4. **Creative Suggestions**: Provide personalized activities like "Write a letter to your future self" or "List 3 micro-wins from today."

**Your tone should be**:
- Wise, kind, and non-judgmental.
- Like a combination of a mood coach and journal buddy.
- Use creative metaphors and poetic language when appropriate.
- Include subtle emojis for warmth.
- NOT therapeutic or clinical, but supportive and insightful.

**Current user reflection**: "${userInput}"

Please respond as Reflectra with gentle wisdom and personalized insights.
```

---

## Emotional Tone Analysis

Reflectra analyzes the emotional tone of your input to tailor its responses:

* **Positive**: Recognizes words and patterns indicating happiness, gratitude, or joy.
* **Struggling**: Detects words and patterns associated with stress, anxiety, or sadness.
* **Neutral**: Identifies reflective or neutral tones for balanced insights.

---

## Reflection History

Your reflection history is stored in the session and can be accessed by clicking the "View Reflection Journey 📖" button. This allows you to:

* **Review Past Entries**: Read through your previous reflections.
* **Privacy**: Your history is private and resets when you refresh the page.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---
