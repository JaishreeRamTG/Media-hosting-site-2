// Import required modules
const express = require("express");
const bodyParser = require("body-parser");

// Initialize the app
const app = express();

// Middleware to parse JSON requests
app.use(bodyParser.json());

// API endpoint to handle "prompt" queries
app.get("/", (req, res) => {
  const prompt = req.query.prompt;

  if (prompt) {
    const data = {
      messages: [
        {
          role: "user",
          content: prompt,
          id: "58rbWde",
        },
      ],
      id: "QAOLIQi",
      previewToken: null,
      userId: null,
      codeModelMode: true,
      agentMode: {},
      trendingAgentMode: {},
      isMicMode: false,
      userSystemPrompt: null,
      maxTokens: 1024,
      playgroundTopP: 0.9,
      playgroundTemperature: 0.5,
      isChromeExt: false,
      githubToken: null,
      clickedAnswer2: false,
      clickedAnswer3: false,
      clickedForceWebSearch: false,
      visitFromDelta: false,
      mobileClient: false,
      userSelectedModel: "gemini-pro",
    };

    const options = {
      method: "POST",
      headers: {
        "User-Agent":
          "Mozilla/5.0 (Linux; Android 13; 220333QAG Build/TKQ1.221114.001) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/129.0.6668.100 Mobile Safari/537.36",
        "Content-Type": "application/json",
        "sec-ch-ua-platform": '"Android"',
        "sec-ch-ua":
          '"Android WebView";v="129", "Not=A?Brand";v="8", "Chromium";v="129"',
        "sec-ch-ua-mobile": "?1",
        origin: "https://www.blackbox.ai",
        "x-requested-with": "mark.via.gp",
        "sec-fetch-site": "same-origin",
        "sec-fetch-mode": "cors",
        "sec-fetch-dest": "empty",
        referer: "https://www.blackbox.ai/?model=gemini-pro",
        "accept-language": "en-GB,en-US;q=0.9,en;q=0.8",
        priority: "u=1, i",
      },
      body: JSON.stringify(data),
    };

    // Make the POST request
    fetch("https://www.blackbox.ai/api/chat", options)
      .then((response) => response.json())
      .then((apiResponse) => {
        res.json({
          status: "Success",
          owner: "@PikaApis",
          response: apiResponse,
        });
      })
      .catch((error) => {
        console.error("Request failed:", error);
        res.json({
          error: "Request failed",
          contact: "@PikaApis",
        });
      });
  } else {
    res.json({
      error: "No prompt provided",
      owner: "@PikaApis",
    });
  }
});

// Start the server
const PORT = process.env.PORT || 3000;
app.listen(PORT, () => {
  console.log(`Server running on port ${PORT}`);
});