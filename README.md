# my-bugs
I will provide details and pocs for some bugs I found. 

    unsigned int efwoffset = 2;
    size_t efwfirmwaresize = std::numeric_limits<unsigned long>::max();
    //size_t size = 20;
    size_t size = 0x40000;
    //size_t size = 0x2800000;
    if(efwoffset + efwfirmwaresize > size) {
        printf("too large");
    }
    else {
        printf("ok");
    }
