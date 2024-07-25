
#!/bin/bash

# Directories to clean
DIR_A="/path/to/directoryA"
DIR_B="/path/to/directoryB"

# Function to clean a directory, keeping only the 5 latest files
clean_directory() {
  local DIR=$1

  # List all files sorted by modification time, and delete all but the 5 newest files
  ls -t "$DIR" | sed -e '1,5d' | xargs -I {} rm -- "$DIR/{}"
}

# Clean directories
clean_directory "$DIR_A"
clean_directory "$DIR_B"

echo "Cleaned $DIR_A and $DIR_B, keeping only the 5 latest files."

