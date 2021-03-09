### Macro Section
.SUFFIXES : .c .o    
CFLAGS = -g         
                 
OBJS = main.o \    
read.o \        
write.o        
SRCS = $(OBJS:.o=.c)   
                      
TARGET = test        

### Command definition Section

$(TARGET): $(OBJS)                  
                $(CC) -o $@ $(OBJS)
dep :                             
                gccmakedpend $(SRCS)
new :                              
                touch $(SRCS) ; $(MAKE)   
clean :                                
                $(RM) $(OBJS) $(TARGET) core 


### Dependency Section
- 여기부터 의존관계 부분
