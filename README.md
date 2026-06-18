# Google Search Quality Evaluator (AI Skill)

This repository contains an AI skill prompt designed to evaluate web content or text against **Google's Search Quality Evaluator Guidelines (SQEG)**.

It instructs AI agents (like Claude, ChatGPT, or Hermes Agent) to act as a Google Quality Rater, analyzing your content for:
- **E-E-A-T** (Experience, Expertise, Authoritativeness, Trustworthiness)
- **Page Quality (PQ)**
- **Needs Met (NM)**
- **Main Content (MC) Quality and Effort**
- **User Experience (UX) and Structure**

## How to use it?

### Option 1: Copy and Paste (For ChatGPT / Claude)
Simply copy the content of the `prompt.md` or `prompt-fa.md` file and paste it into your AI chat, followed by your text or URL.

### Option 2: Use in Hermes Agent
If you are using [Hermes Agent](https://github.com/NousResearch/Hermes-Agent), you can install this skill directly by adding the `SKILL.md` to your `~/.hermes/skills/google-sqeg-evaluator/` directory.

## What is Google's SQEG?
The [Search Quality Evaluator Guidelines](https://static.googleusercontent.com/media/guidelines.raterhub.com/en//searchqualityevaluatorguidelines.pdf) is a ~170-page document provided by Google to its human raters. It defines what Google considers "high-quality" content. It heavily focuses on E-E-A-T, especially for **YMYL** (Your Money or Your Life) topics.

## Output Format
The AI will generate a structured report including:
1. 📊 Overview
2. 🎯 Page Quality and E-E-A-T Assessment
3. 💡 Main Content Assessment
4. 🎨 Structure and UX Evaluation
5. 🛠️ Actionable Recommendations
