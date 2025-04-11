# FlightAI: Multi-Modal Airline Customer Support Assistant  

✨ *An intelligent assistant blending voice, visuals, and real-time data to transform airline customer service.*  

## Key Features  

| Feature                | Technology Used          | Benefit                                                                 |
|------------------------|--------------------------|-------------------------------------------------------------------------|
| **Instant Pricing**    | GPT-4 Function Calling   | Fetch real-time ticket prices for 12+ global destinations.              |
| **Voice Interaction**  | OpenAI TTS (Onyx voice)  | Natural-sounding responses for accessible, hands-free support.          |
| **Destination Art**    | DALL·E 3 Image Generation| Generate vibrant pop-art travel inspiration images.                     |
| **Chat UI**            | Gradio                   | User-friendly interface with conversation history and image display.    |

## How It Works  
1. **User Query**: Ask about flight prices (e.g., *"How much to Tokyo?"*).  
2. **AI Processing**:  
   - Calls `get_ticket_price()` tool for real-time data.  
   - Generates TTS audio and optional destination artwork.  
3. **Multi-Modal Response**: Returns price, speaks the answer, and shows a visual.  

## Tech Stack  
- **Core AI**: OpenAI GPT-4 (function calling)  
- **Voice**: `openai.audio.speech` (TTS)  
- **Images**: DALL·E 3 API  
- **UI**: Gradio (Python)  

## Business Impact  
- **24/7 Support**: Reduce call center loads.  
- **Upsell Opportunities**: Visuals inspire travel bookings.  
- **Accessibility**: Voice-first design aids diverse travelers.  

> *"FlightAI demonstrates how generative AI can create delightful, efficient customer experiences in aviation."*  
