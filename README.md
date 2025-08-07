# reddit-sre-content-agent
An intelligent n8n workflow that transforms trending DevOps discussions into actionable blog post ideas for AI SRE marketing teams.


<img width="888" height="380" alt="Screen Shot 2025-08-06 at 10 09 53 PM" src="https://github.com/user-attachments/assets/faf8e492-351f-4507-829a-4704261e6146" />


## Output Email
<img width="1080" height="637" alt="Screen Shot 2025-08-07 at 2 03 47 PM" src="https://github.com/user-attachments/assets/f1a99263-f0f3-4d1a-9d44-22acbab94da8" />



## What It Does

This automated content discovery agent monitors popular DevOps subreddits (r/devops, r/sre, r/kubernetes) and generates two types of weekly content insights:

1.  **Top 10 Trending Posts** - Curated high-engagement discussions from the DevOps community
2.  **10 Original Blog Ideas** - AI-generated content concepts that directly address problems discussed in those trending posts

##  Key Features

-   **Multi-Subreddit Monitoring** - Tracks discussions across DevOps, SRE, and Kubernetes communities
-   **Smart Content Filtering** - Automatically excludes job posts, deleted content, and low-engagement discussions
-   **AI-Powered Analysis** - Uses OpenAI to extract pain points, technical context, and content opportunities
-   **Direct Problem-Solution Mapping** - Each blog idea directly addresses specific community pain points
-   **Weekly Email Delivery** - Formatted HTML reports sent directly to your inbox
-   **Zero Manual Effort** - Fully automated workflow triggered on-demand

##  How It Works

1.  **Content Discovery** - Fetches top 50 posts from DevOps-related subreddits
2.  **Smart Filtering** - Removes irrelevant content and selects top 10 high-engagement posts
3.  **AI Analysis** - Analyzes each post to identify pain points and technical context
4.  **Content Ideation** - Generates blog ideas that solve the specific problems discussed
5.  **Report Generation** - Compiles everything into a professional HTML email report
6.  **Automated Delivery** - Sends weekly insights directly to your marketing team


## Technical Stack

-   **Workflow Engine**: n8n (Node-RED alternative)
-   **AI Processing**: OpenAI GPT-4o-mini
-   **Data Source**: Reddit API (OAuth2)
-   **Email Delivery**: SMTP integration
-   **Content Processing**: JavaScript for data filtering and HTML generation

## Setup Requirements

### Prerequisites

-   n8n instance (cloud or self-hosted)
-   Reddit account with API access
-   OpenAI API key
-   SMTP email configuration

### Credentials Needed

1.  **Reddit OAuth2** - Connect your Reddit account
2.  **OpenAI API** - For content analysis and ideation
3.  **SMTP** - For email delivery (Gmail, Outlook, etc.)

##   Perfect For

-   **AI SRE Product Marketing Teams** - Generate relevant content ideas based on real community problems
-   **Developer Relations Teams** - Stay connected to community pain points and trending discussions
-   **Technical Content Writers** - Get data-driven inspiration for blog posts and newsletters
-   **Product Managers** - Understand what problems developers are actually discussing

##   Business Value

-   **Reduces Research Time** - Automates hours of manual Reddit browsing and analysis
-   **Increases Content Relevance** - Blog ideas directly address real community problems
-   **Improves Content Strategy** - Data-driven approach to content planning
-   **Enhances Community Connection** - Stay plugged into what developers are actually discussing
-   **Scales Content Discovery** - Consistent weekly insights without manual effort

##   Customization Options

-   Adjust subreddit targets (add r/CloudNative, r/microservices, etc.)
-   Modify post engagement thresholds
-   Customize AI prompts for different content angles
-   Change email frequency and formatting
-   Add additional content filtering rules

##   Sample Output

**Report includes:**

-   "How AI SRE Solves Kubernetes DNS Resolution Issues" (based on actual DNS debugging discussion)
-   "Automating Multi-Cluster Configuration Management" (inspired by Sveltos deployment challenges)
-   "AI-Powered Kubernetes Architecture Visualization" (addressing KubeDiagrams pain points)

Each idea includes specific technical context, target audience level, and clear AI SRE product positioning.
