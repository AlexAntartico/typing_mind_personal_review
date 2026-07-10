# Deep research with Firecrawl and Serp

I have to say this [video](https://www.youtube.com/watch?v=5N-6TjEhTCg) is pretty neat. Setting up the plugins is as easy as going to `Plugins` / `Plugins` / `Deep Research`.

<img width="942" height="463" alt="Screenshot_20260709_232630" src="https://github.com/user-attachments/assets/f240a784-2112-4fc6-8da8-1475f5f45ee7" />

Paste your keys and select the mode. I'm using free plans for both APIs, so I selected the lightweight mode.

<img width="942" height="540" alt="Screenshot_20260709_233046" src="https://github.com/user-attachments/assets/d6dcda8f-e5b2-47fe-910f-3a0a3ed34c35" />

Note the plan has 4 functions:

1. Research Plan - The model uses this function to break the topic into research questions, decide what kind of sources are needed, and define the search strategy.
2. Search Web - This uses your configured SerpAPI key. SerpAPI acts as the search layer, returning search results from the web.
3. Extract Web Page - This uses Firecrawl to clean up a page and pull out meaningful text, excluding navigation menus, ads, cookie banners, sidebars, and layout noise.
4. Read Full Web Page - Also powered by Firecrawl; instead of extracting a focused version, it attempts to retrieve and process the whole page.

And to keep it cheap in tokens and API calls, I refined this prompt and added a very important **API Budget** section. It's always a good idea to put some guardrails on the API calls if you don't want to go broke.

```markdown
# Act as a research analyst.

Research the effectiveness of COVID-19 vaccines in reducing severe disease among adults in the United States.

## Research workflow:

1. Generate a concise research plan.
2. Search the web for authoritative sources.
3. Limit yourself to a maximum of 3 search results.
4. Read only the pages necessary to answer the question (maximum 3 pages).
5. Prioritize:
   - CDC
   - NIH
   - JAMA
   - NEJM
6. Ignore news articles, blogs, opinion pieces, social media, and commercial websites.
7. Stop searching once sufficient evidence has been collected.

## Deliverables:

- Executive Summary in Markdown format
- Evidence Table
    - Source
    - Publication date
    - Study type
    - Main conclusion
- Confidence Assessment
- Limitations
- References

## API Budget:

- Maximum 2 research plans.
- Maximum 4 search queries.
- Maximum 6 search results.
- Maximum 6 page reads.
- Do not perform follow-up searches unless no authoritative sources are found.
- Prefer extracting only the relevant sections instead of reading entire websites.
```

Grok seems to struggle with plugins when I keep it in thinking mode, so for this query I disabled it.

<img width="946" height="1043" alt="image" src="https://github.com/user-attachments/assets/b4744cb2-c1db-4d9c-b436-dd0647fb4a97" />

# Conclusions

**This could be a keeper for my personal workflows.** I mainly use Perplexity Computer to research and fact-check the links and information returned. This might be a replacement for my specific use case. It may not be the same for everyone, as `Perplexity Computer` allows you to navigate through websites, click through pages, execute code, etc.

Pros: more control over source limits; you can specify, at a granular level, the number of reads.  
Cons: two APIs, two subscriptions; you can stay on the free plan only with a tight API call budget; does not interact with sites the way Perplexity's Computer does.

I asked ChatGPT for a comparison and here are the results:

> **Strategic way to think about it**
> 
> Use TypingMind Deep Research when the deliverable is a research artifact: briefing, evidence table, literature scan, market summary, policy comparison, or source-backed report.
> 
> Use Perplexity Computer Mode when the deliverable requires interaction with websites or apps: navigating dashboards, filling forms, collecting data from pages, working across tabs, monitoring changes, or executing workflow steps. Perplexity’s Comet product is positioned around automating tasks, researching the web, and organizing things like email from within an AI browser.

I will experiment more with this feature and see if I can stay below the usage, I dont really need an extra monthly subscription.

I have also attached in this folder the report generated and the chat transcript

## Stats for nerds

Total messages: 21
Total tokens spent: 164,334 (estimated)
Total tokens cached: 105,344
Estimated size: 182.79 KB
Estimated cost: $0.1866
Models(1): Grok 4.5 (grok-4.5)
