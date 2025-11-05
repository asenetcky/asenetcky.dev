if (interactive()) {

  print("Using P3M Linux Binaries.")
  if (Sys.info()["sysname"] == "Linux")
  options(
        repos = c(
          CRAN = sprintf(
            "https://packagemanager.posit.co/cran/latest/bin/linux/manylinux_2_28-%s/%s",
            R.version["arch"],
            substr(getRversion(), 1, 3)
          )
        )
      )
}

source("renv/activate.R")
