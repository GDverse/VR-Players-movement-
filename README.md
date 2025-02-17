PlayerMovement1 - First-Person Character Controller

Description

PlayerMovement1 is a first-person character controller for Unity, featuring smooth movement, sprinting, crouching, jumping, and super jumps. It provides a flexible and optimized movement system suitable for FPS, adventure, or exploration games.

Features

Basic Movement: Move in all directions using WASD keys.

Sprint: Hold Left Shift to run.

Jumping:

Space for a normal jump.

E for a Super Jump with increased height.

Crouching: Press Q to toggle crouch mode, which lowers height and reduces speed.

Camera Adjustments: Smooth height transition when crouching.

Mouse Look: Adjustable first-person camera rotation.

Gravity Handling: Smooth falling physics.

Installation & Setup

Clone or download this repository.

Open your Unity project.

Add a GameObject with a CharacterController component.

Attach the PlayerMovement1.cs script to the GameObject.

Assign a Camera to the playerCamera field in the Inspector.

Adjust movement speeds, jump power, and sensitivity as needed.

Controls

Action

Key

Move Forward

W

Move Backward

S

Move Left

A

Move Right

D

Jump

Space

Super Jump

E

Sprint

Left Shift

Toggle Crouch

Q

Mouse Look

Move mouse

Requirements

Unity 2021+ (Tested on Unity 2022+)

CharacterController component attached to the player object.

Camera assigned for first-person view.

Customization

Modify the following public variables in the script to adjust the player's movement:

walkSpeed - Adjust walking speed.

runSpeed - Adjust sprinting speed.

jumpPower - Height of the normal jump.

superJumpPower - Height of the super jump.

crouchSpeed - Adjust speed while crouching.

lookSpeed - Adjust camera sensitivity.

gravity - Modify gravity strength.

License

This project is open-source and available under the MIT License. Feel free to modify and use it in your projects!

Contributions

Pull requests are welcome! If you encounter any bugs or have suggestions, feel free to open an issue.

Author

Developed by GOULIOS DOROPOYULOS (GDVERSE) 
