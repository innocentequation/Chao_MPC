# Dilla Shrine Sampler

A browser-based MPC-style sampler inspired by J Dilla's setup, featuring:
- 16-pad grid with keyboard mapping
- WaveSurfer.js for waveform visualization
- SP-1200-style audio processing
- 432 Hz tuning option
- Vintage sampler characteristics

## Local Development

1. Clone this repository
2. Navigate to the project directory
3. Start the local server:
   ```bash
   python3 -m http.server 8000
   ```
4. Open http://localhost:8000 in your browser

## Deployment

### Option 1: Static Site Hosting (e.g., GitHub Pages, Netlify)

1. Fork this repository
2. Enable GitHub Pages in your repository settings
   - Set source to main branch
   - Your sampler will be available at `https://[your-username].github.io/[repo-name]`

### Option 2: Traditional Web Hosting

1. Upload the following files to your web server:
   - `index.html` (renamed from MPC_index.html)
   - Any additional assets

### Option 3: Custom Server

If you need backend features, consider:
- Node.js with Express
- Python with Flask/Django
- PHP
- etc.

## Usage

1. Click "LOAD SAMPLE" to load an audio file
2. Use the 16-pad grid or keyboard shortcuts to trigger samples
3. Adjust volume and effects as needed
4. Save your beats using the "SAVE BEAT" button

## Keyboard Mapping

- Top Row: 4, 5, 6, 7
- Second Row: E, R, T, Y
- Third Row: D, F, G, H
- Bottom Row: X, C, V, B

## Browser Support

Requires a modern browser with Web Audio API support:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

## License

MIT License - See LICENSE file for details 