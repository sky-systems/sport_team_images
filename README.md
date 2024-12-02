# Team Images

This documentation provides information on configuring team images for our FiveM sportsbetting script, which displays real-time sports odds along with team images. The script pulls images from this GitHub repository. 

## Adding Missing Team Images

If the icons for your teams are missing, you can contribute by adding them to the repository. Follow these steps to add new team images:

1. **Create a Pull Request**: Fork the [sport_team_images repository](https://github.com/sky-systems/sport_team_images), add your images to the `teams/` folder in your fork, and create a pull request.

2. **Image Requirements**:
    - **Format**: PNG
    - **Size**: Not too large, maximum 500x500 pixels
    - **Naming Convention**: The image must be named exactly as the team name appears in the UI, but without spaces. For example:
        - **St. Louis Cardinals** should be named `St.LouisCardinals.png`

3. **Submission**: After ensuring your image meets the requirements, submit a pull request with the new image.

### Example Image Naming

Here are some examples of how team names should be formatted for the images:

- **Team Name**: St. Louis Cardinals
  - **Image File Name**: `St.LouisCardinals.png`
- **Team Name**: Bayern Munich
  - **Image File Name**: `BayernMunich.png`
- **Team Name**: New York Yankees
  - **Image File Name**: `NewYorkYankees.png`

## Need Help?

If you need assistance with adding team images, you can open a ticket on our Discord server. Our support team will guide you through the process.

## Example Pull Request

To add an image for the "St. Louis Cardinals":

1. **Fork the Repository**: Click on the "Fork" button on the repository page.
2. **Clone the Repository**: Clone your forked repository to your local machine.
    ```bash
    git clone https://github.com/your-username/sport_team_images.git
    ```
3. **Add the Image**: Save the image as `St.LouisCardinals.png` and place it in the `teams/` folder.
4. **Commit and Push**: Commit your changes and push them to your forked repository.
    ```bash
    git add teams/St.LouisCardinals.png
    git commit -m "Add image for St. Louis Cardinals"
    git push origin main
    ```
5. **Create Pull Request**: Go to the original repository and create a pull request from your fork.

## Conclusion

By following these guidelines, you can ensure that your team images are correctly added and displayed in the FiveM script. If you encounter any issues or need further assistance, don't hesitate to reach out to our support team on Discord.

For any questions or support, please contact our support team via our Discord server.
