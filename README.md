# bashscripts
Some bash scripts tip that I have collected over the internet

### Utils.sh (http://natelandau.com/bash-scripting-utilities/)
#### Pre-define some functions, utils for bash scripts support the following
Colors, Header, Logging
Testing application, package are existed, check the OS
Sending notifications to push over


#### Sample

#!/bin/bash   

source $HOME/Library/init/utils.sh   

e_header "I am a sample script"   
e_success "I am a success message"   
e_error "I am an error message"   
e_warning "I am a warning message"   
e_underline "I am underlined text"   
e_bold "I am bold text"   
e_note "I am a note"   
