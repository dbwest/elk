# Breakout Session 1

## Shakespeare

### Summary

This lab involves analyzing all the lines from all the characters in Shakespeare.

### Concepts

- Importing Data
- Exploring Basic Visualizations

### Instructions

**1. Visit the appropriate ELK Url for your team.**

- Cyan: https://cyan.mi7.dev
- Magenta: https://magenta.mi7.dev
- Yellow: https://yellow.mi7.dev

**2. Click `Log in with Elasticsearch`**

![login](assets/login.PNG)

**3. Log in with the credentials you got during pre-prep.**

**4. Click the `hamburger menu` at the top left**

![hamburger](assets/hamburger.PNG)

**5. Click `Machine Learning`**

![ml](assets/ml2.PNG)

**6. Click `Data Visualizer`**

![dataviz](assets/dataviz.PNG)

**7. Click `Upload File`**

![uploadfile](assets/uploadfile.PNG)

**8. Drag 'n Drop `shakespeare.json` in (will have a slightly diff name than in the below picture):**

![drag_n_drop](assets/drag_n_drop.PNG)

**9. Click `Import` This is very important.**

![success_shakes](assets/import.PNG)

**10. Name your index `shakespeare`. Do not forget to click `Import` again.**

![name_idx_shakes](assets/name_idx_shakes.PNG)

**11. Wait while Kibana 'does its magic'. When it is done you can go to the next step.**

![do_the_magic](assets/do_the_magic.PNG)

**12. Open up the `hamburger` menu on the left and go to `Discover`.**

![discover](assets/discover.PNG)

**13. We are now going to start exploring the Shakespeare data. We will start by seeing all lines spoken by the character HAMLET type `speaker : HAMLET` in the search bar. Then press `enter`**

![search_bar](assets/search_bar.PNG)

**14. Hmm the lines look a little cluttered.**

![cluttered](assets/cluttered.PNG)

**Let's fix that. Hover over `text_entry`, the field with each characters lines, and click the `add` button that appears on mouse-over**

![mouse_over](assets/mouse_over.png)

**That's better!**

![better](assets/better.PNG)

**15. Now we will do some CSI. We are going to see which characters have the most lines about 'murder'. Put the following in the search bar. `text_entry : "*murder*"`**

![csi](assets/csi.PNG)

**16. Now let's get a histogram of all characters talking about "murder" and make a bar chart. First click on `speaker` on the left side of `Discover` to expand a list of speakers of lines from shakespeare and show the counts for each speaker.**

**Click the `Visualize` button under the speakers**

![speakers](assets/speakers.PNG)

**You should see a bar chart**

![speaker_bar](assets/speaker_bar.PNG)

**17. You may now be wondering... Is Lady Macbeth in this dataset?....**

**Extra credit: Determine if Lady Macbeth is in the dataset.**

**Extra extra credit: make a `tag cloud` with all the speakers (bigger text for speaker's name if they have more lines)**
