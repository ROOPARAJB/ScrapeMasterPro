### Title: ScrapeMaster Pro

**ScrapeMaster Pro** is your ultimate web scraping tool, crafted to effortlessly extract emails, phone numbers, and social media accounts from websites. Use the gathered data for research or direct contact with site owners.

**Installation & Setup**

Get started with ScrapeMaster Pro by following these easy steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/champmq/TheScrapper.git
   ```

2. **Navigate to the directory:**

   ```bash
   cd TheScrapper
   ```

3. **Install the dependencies:**

   ```bash
   pip3 install -r requirements.txt
   ```

**Usage**

ScrapeMaster Pro offers several usage options:

1. **Simple scan:**

   ```bash
   python3 TheScrapper.py --url URL
   ```

2. **Scan and crawl found URLs:**

   ```bash
   python3 TheScrapper.py --url URL --crawl
   ```

3. **Retrieve detailed info about found social media accounts:**

   ```bash
   python3 TheScrapper.py --url URL -s
   ```

For additional command-line arguments and options, refer to the help menu:

```bash
python3 TheScrapper.py -h
```

To remove the banner, simply add the `-b` flag.

**Adding More Social Media Sites**

To add more social media sites for scraping, append them to the `socials.txt` file. Feel free to contribute by submitting a pull request to share your additions with the community.

**Known Issues**

When using a website already included in the `socials.txt` file, the `--sm` flag may produce less useful output. To avoid this, consider excluding such URLs or refraining from using the `--sm` flag.
