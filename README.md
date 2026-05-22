```markdown
# SaaS para Clínicas Dentales

SaaS para Clínicas Dentales es una aplicación diseñada para optimizar la gestión de citas, automatizar recordatorios con inteligencia artificial y realizar el seguimiento de tratamientos en clínicas dentales. Este sistema es ideal para clínicas que buscan mejorar la eficiencia operativa y la satisfacción del paciente.

## Tech Stack

- **Frontend**: Next.js 15, Tailwind CSS v4
- **Backend**: Supabase
- **Payments**: Stripe
- **AI**: OpenAI, Claude, Gemini

## Prerequisites

- Node.js 18+
- Supabase account
- API keys for OpenAI, Claude, Gemini, and Stripe

## Installation

1. **Clone the repository**: 
   ```bash
   git clone https://github.com/yourusername/saas-clinicas-dentales.git
   cd saas-clinicas-dentales
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Setup environment variables**:
   Create a `.env.local` file in the root directory and configure the following variables:

4. **Run the development server**:
   ```bash
   npm run dev
   ```

## Environment Variables

| Variable Name       | Description                      |
|---------------------|----------------------------------|
| `NEXT_PUBLIC_SUPABASE_URL` | Supabase project URL          |
| `NEXT_PUBLIC_SUPABASE_ANON_KEY` | Supabase anonymous key         |
| `STRIPE_SECRET_KEY` | Stripe secret key                |
| `OPENAI_API_KEY`    | OpenAI API key                   |
| `CLAUDE_API_KEY`    | Claude API key                   |
| `GEMINI_API_KEY`    | Gemini API key                   |

## Project Structure

- **/components**: Reusable UI components.
- **/pages**: Next.js pages.
- **/lib**: Utility functions and configurations.
- **/styles**: Global styles and Tailwind CSS configurations.
- **/api**: API route handlers.

## Key Features

- **Appointment Management**: Schedule, modify, and track appointments.
- **Automated Reminders**: Send AI-driven reminders to patients.
- **Treatment Follow-up**: Monitor and document patient treatment plans.
- **Secure Payments**: Process payments via Stripe.

## Deployment to Vercel

1. **Connect your repository** to Vercel.
2. **Set environment variables** in Vercel settings.
3. **Deploy**: Push to your main branch, and Vercel will automatically deploy your app.

## API Documentation

### Main Endpoints

- **GET /api/appointments**: Retrieve all appointments.
- **POST /api/appointments**: Create a new appointment.
- **PUT /api/appointments/{id}**: Update an appointment.
- **DELETE /api/appointments/{id}**: Delete an appointment.
- **POST /api/reminders**: Trigger an automated reminder.

## License

This project is licensed under the MIT License.
```
