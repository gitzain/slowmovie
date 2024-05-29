# SlowMovie
Transform your Waveshare 7.5-inch e-paper screen into a dynamic art display by showcasing video frames in a slow, frame-by-frame progression, creating a unique and captivating visual experience.


## Table of content
- [Motivation](#motivation)
- [Screenshots](#screenshots)
- [Installation & Usage](#installation--usage)
    - [Installation](#installation)
    - [Usage](#usage)
- [Contributing](#contributing)
- [History](#history)
- [Credits](#credits)
- [License](#license)


## Motivation
I wanted to play around with e-ink technology and create something visually stunning as a home display item. When I stumbled upon a [Hackaday article](https://hackaday.com/2020/08/23/e-paper-display-shows-movies-very-very-slowly/), it provided the perfect inspiration. The idea of displaying movies frame by frame on a Waveshare 7.5-inch e-paper screen sounded both quirky and mesmerizing. Most of this project is me hacking together other people's brilliant work to suit my needs and keep things simple. Big thanks to the original creators, especially [Tom Whitwell's SlowMovie on GitHub](https://github.com/TomWhitwell/SlowMovie), for their inspiring contributions.

## Screenshots
[Click here for a look at the finished product and screenshots from Ton's article](https://debugger.medium.com/how-to-build-a-very-slow-movie-player-in-2020-c5745052e4e4)


## Installation & Usage
### Installation
1. **Clone the Repository and Install Dependencies:**
   ```bash
   git clone https://github.com/yourusername/SlowMovie.git
   cd SlowMovie
   pip install -r requirements.txt
   ```

2. **Enable SPI on Your Raspberry Pi:**
   Ensure SPI is enabled on your Raspberry Pi via `raspi-config`:
   ```bash
   sudo raspi-config
   ```
   Navigate to `Interfacing Options` -> `SPI` and enable it.

3. **Install the Waveshare E-Paper Library:**
   Follow the [Waveshare instructions](https://www.waveshare.com/wiki/7.5inch_e-Paper_HAT) for installing the E-Paper library.

4. **Set Up Video Files:**
   Place your `.mp4` video files in the existing `videos` directory.

### Usage
1. **Run the Script:**
   ```bash
   python slowmovie.py
   ```


## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Added some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## History 
09/04/22: v1 published to github.  


## Credits
- Created by [Zain Khan](https://iamzain.com).
- Heavily inspired by:
  - [E-Paper Display Shows Movies Very, Very Slowly](https://hackaday.com/2020/08/23/e-paper-display-shows-movies-very-very-slowly/) from Hackaday.
  - [Very Slow Movie Player](https://bryan.medium.com/very-slow-movie-player-499f76c48b62) by Bryan Boyer.
  - [SlowMovie](https://github.com/TomWhitwell/SlowMovie) by [Tom Whitwell](https://github.com/TomWhitwell).
- Template for this README is [template-readme](https://github.com/gitzain/template-README) created by [Zain Khan](https://iamzain.com).


## License
See the LICENSE file in this project's directory.
