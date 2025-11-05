# .Rprofile in project root
py <- if (.Platform$OS.type == "windows") {
  normalizePath("stats/Scripts/python.exe", winslash = "\\", mustWork = TRUE)
} else {
  normalizePath("stats/bin/python", mustWork = TRUE)
}

Sys.setenv(RETICULATE_PYTHON = py)       # set BEFORE loading reticulate
# Sys.setenv(RETICULATE_PYTHON_FALLBACK = "0")  # optional: prevent fallback

# .Rprofile (project)
# library(reticulate)
suppressMessages(library(reticulate))
# Use the stats venv in the project folder
# use_virtualenv(py, required = TRUE)
