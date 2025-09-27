# Obsidian Test

# Obsidian to Quartz v4

    docker run --rm -itp 8080:8080 -p 3001:3001 -v ./content:/usr/src/app/content $(docker build -q .)

## Obsidian to Cosma

Edit the markdown files with frontmatter for types.

Convert Obsidian vault toward Cosma

    python obsidian2cosma.py -i content -o content-cosma

Create Cosmoscope file

    npx cosma modelize --p cosma

Open Cosmoscope file in browser

    php -S localhost:9999

