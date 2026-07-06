Drop project images / videos here (jpg, png, mp4).
Then in src/Projects.res, swap a Placeholder("...") for:
  Image(Nav.asset("projects/yourfile.jpg"), "description")
  Video(Nav.asset("projects/yourclip.mp4"))
  Pdf(Nav.asset("pdfs/yourfile.pdf"), "Label")
