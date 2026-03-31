#!/bin/bash
# Script 5: Open Source Manifesto Generator

echo "===== Open Source Manifesto Generator ====="

# User input
read -p "1. Name one open-source tool you use daily: " TOOL
read -p "2. In one word, what does 'freedom' mean to you? " FREEDOM
read -p "3. Name one thing you would build and share: " BUILD

DATE=$(date '+%d %B %Y')
OUTPUT="manifesto_$(whoami).txt"

# Generate manifesto
echo "On $DATE, I believe in open source." > $OUTPUT
echo "Using $TOOL, I understand that freedom means $FREEDOM." >> $OUTPUT
echo "I aim to build $BUILD and share it freely with the world." >> $OUTPUT

# Output
echo "-------------------------------------"
echo "Manifesto saved to $OUTPUT"
echo "-------------------------------------"
cat $OUTPUT
