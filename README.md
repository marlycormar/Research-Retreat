### Current poster template

    HTML Poster (the ReLaXed Style)

### To render PDF & html

    pagedown::chrome_print("Poster.Rmd")

### To render PDF only

    pagedown::chrome_print("Poster.html")

### Check spelling

    library(spelling)
    spell_check_files("./Poster.Rmd")
