Certainly, here's the updated README with the added information about the course:

# SpaceCraft-PyOpenGL

![SpaceCraft-PyOpenGL Demo](https://github.com/ShakeefAhmedRakin/SpaceCraft-PyOpenGL/assets/112527326/25371ca3-8355-45e1-a32b-b7ebfa050086)

SpaceCraft-PyOpenGL is an interactive animation built using the PyOpenGL library. This project simulates the movement of a spacecraft and its journey through space towards three larger stars. Users can control the spacecraft's movement using the W, A, S, and D keys on the keyboard. This project was developed as part of the CSE423: Computer Graphics course at <a href="https://www.bracu.ac.bd/">BRAC University</a>.

## Features

- Control the spacecraft using the W, A, S, and D keys for movement achieved through translation.
- Illusion of heading towards three larger stars (red, yellow, blue) achieved through scaling.
- Background simulation with randomly generated white and yellow pixels for starry effect.
- Asteroid visuals using brown circles in the background.
- Utilization of Midpoint Line Algorithm and Midpoint Circle Algorithm for all the shapes generated.
- Utilization of transformation techniques like translation and scaling.

## Demo

![Demo Output](https://github.com/ShakeefAhmedRakin/SpaceCraft-PyOpenGL/assets/112527326/fad4e5f0-c185-449b-929d-0fc7c65d3bcd)

The above image showcases the output of the animation after running for a few minutes.

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/ShakeefAhmedRakin/SpaceCraft-PyOpenGL.git
   ```

2. Install the required dependencies:

   ```bash
   pip install PyOpenGL-3.1.6-cp311-cp311-win_amd64.whl
   pip install PyOpenGL_accelerate-3.1.6-cp311-cp311-win_amd64.whl
   pip install numpy
   ```

3. Run the script.

4. Use the following keys to control the spacecraft:
   - **W**: Move forward
   - **A**: Move left
   - **S**: Move backward
   - **D**: Move right

