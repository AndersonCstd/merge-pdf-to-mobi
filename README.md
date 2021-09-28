# merge-pdf-to-mobi
Merge .pdf files in .mobi with kcc and pdftoppm

Install the requirements (I assume that you alredy have the apps Kindle Comic Convert and the pdftoppm instaled on your **linux-machine**).
Move the merge-pdf-to-mobi to your $PATH.

## Usage

python merge-pdf-to-mobi --pdf PDF_FILES \
  --cover LOCATION_TO_THE_COVER \
  --output OUTPUT_FILE_NAME \
  --server (y/n)
