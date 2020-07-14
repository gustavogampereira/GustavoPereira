#install.packages("blogdown")
blogdown::install_hugo(version = "0.69.0", force = TRUE)
library(blogdown)

# is your version less than the minimum version?
hugo_version() 
# if yes, then do this
update_hugo(force = TRUE)

new_site(theme = "gcushen/hugo-academic", 
         sample = TRUE, 
         theme_example = TRUE, 
         empty_dirs = TRUE,
         to_yaml = TRUE)

blogdown::serve_site()
