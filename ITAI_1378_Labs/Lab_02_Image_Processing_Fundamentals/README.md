L02: Image Processing Fundamentals 
Due Jun 10 by 11:59pm Points 100 Submitting a file upload
Lab 02: Image Processing Fundamentals
Student Instructions and Guidelines
📋 Lab Overview
Lab Title: From Pixels to Perception: Image Processing FundamentalsDuration: 45 minutes hands-on + reflection timePlatform: Google Colab (Free Version)Due Date: [Insert due date]Points: 100 points total (80 points lab + 20 points reflection journal)
🎯 Learning Objectives
By completing this lab, you will:
1.Understand how computers represent images as numerical matrices
2.Implement fundamental image processing operations from scratch
3.Apply traditional image processing techniques using OpenCV and Pillow
4.Connect theoretical concepts to practical applications
5.Analyze the relationship between traditional methods and modern AI tools
6.Reflect on the implications and applications of image processing
📁 File Naming Convention
IMPORTANT: All submitted files must follow this exact naming convention:
Lab Notebook:
Plain Text
L02_YourLastName_YourFirstName_ITAI1378.ipynb
Reflection Journal:
Plain Text
J02_YourLastName_YourFirstName_ITAI1378.pdf
Examples:
•L02_Smith_John_ITAI1378.ipynb
•J02_Smith_John_ITAI1378.pdf
🚀 Getting Started
Step 1: Access the Lab
1.Download the lab notebook: image_processing_lab.ipynb
2.Open Google Colab in your web browser: colab.research.google.comLinks to an external site.
3.Upload the notebook to Colab:
•Click "File" → "Upload notebook"
•Select the downloaded .ipynb file
4.Rename your notebook using the proper naming convention
Step 2: Environment Setup
1.Run the first cell to install required packages
2.Verify all imports work correctly
3.Check that sample images load properly
Step 3: Work Through the Lab
1.Read each markdown section carefully - they connect directly to lecture concepts
2.Run cells in order - don't skip ahead
3.Modify code where indicated to experiment
4.Take notes as you work for your reflection journal
📚 Lab Structure and Requirements
Part 1: Digital Image Fundamentals (10 minutes)
Requirements:
Successfully load and analyze the test image
Examine image properties (shape, data type, value range)
Separate and visualize RGB channels
Convert to grayscale using different methods
Answer inline questions about matrix representation
Deliverables:
•Working code cells with output
•Completed analysis of image properties
•Comparison of grayscale conversion methods
Part 2: Basic Image Operations (10 minutes)
Requirements:
Implement brightness and contrast adjustments from scratch
Apply different convolution kernels (blur, edge detection, sharpening)
Understand and explain the difference between point and neighborhood operations
Experiment with different kernel values
Deliverables:
•Custom brightness/contrast functions
•Successful application of various filters
•Visual comparison of different operations
Part 3: Advanced Processing Techniques (10 minutes)
Requirements:
Analyze histograms and apply histogram equalization
Implement geometric transformations (scaling, rotation, translation)
Apply CLAHE enhancement
Compare results of different enhancement methods
Deliverables:
•Histogram analysis with visualizations
•Multiple geometric transformations
•Before/after comparisons with statistical analysis
Part 4: Creative Exploration (5 minutes)
Requirements:
Create artistic effects by combining multiple operations
Implement at least one custom filter combination
Document your creative process and choices
Deliverables:
•Original artistic effects
•Documentation of processing pipeline
•Creative combination of techniques
Part 5: AI Connection (5 minutes)
Requirements:
Run the AI simulation code
Analyze how traditional operations relate to AI methods
Connect to Nano Banana and modern tools discussed in class
Deliverables:
•Understanding of AI-traditional connections
•Completed simulation analysis
📝 Submission Requirements
Lab Notebook Submission
Your completed notebook must include:
1.All cells executed with visible output
2.Inline responses to questions throughout the lab
3.Code modifications where requested
4.Personal experiments beyond the basic requirements
5.Clear documentation of your work
Code Quality Standards:
All cells run without errors
Code is well-commented
Variables have meaningful names
Output is clearly visible
Experiments are documented
Additional Requirements:
Add at least 3 personal experiments beyond the basic lab
Include text explanations for your experimental choices
Compare results quantitatively where possible
Connect findings to real-world applications
📖 Reflection Journal Requirements
Create a 1-2 page reflection journal addressing the following:
Section 1: Technical Understanding (40%)
•What was the most surprising discovery about how images are represented?
•How do the mathematical operations we implemented relate to visual effects?
•Which technique was most challenging to understand and why?
Section 2: Connections and Applications (40%)
•How do today's lab activities connect to the Nano Banana demonstration from class?
•What real-world applications can you envision for the techniques you learned?
•How might you combine traditional and AI approaches in a future project?
Section 3: Personal Reflection (20%)
•What aspect of image processing interests you most for further exploration?
•How has this lab changed your understanding of digital photography and image editing?
•What questions do you still have about image processing?
Journal Format Requirements:
•Length: 1-2 pages  (not in bullet points)
•Format: PDF document
•Header: Include your name, course, and date
🎯 Grading Rubric
Lab Notebook (80 points)
Component	Excellent (A)	Good (B)	Satisfactory (C)	Needs Improvement (D/F)
Technical Execution (25 pts)	All code runs perfectly, demonstrates mastery	Minor issues, good understanding	Some errors, basic understanding	Major errors, limited understanding
Completeness (20 pts)	All sections completed with extras	All sections completed	Most sections completed	Many sections incomplete
Understanding (20 pts)	Deep insights, excellent explanations	Good understanding shown	Basic understanding	Limited understanding
Experimentation (15 pts)	Creative, well-documented experiments	Good experiments	Basic experiments	Minimal experimentation
Reflection Journal (20 points)
Component	Excellent (A)	Good (B)	Satisfactory (C)	Needs Improvement (D/F)
Technical Reflection (8 pts)	Deep, insightful analysis	Good technical understanding	Basic reflection	Superficial analysis
Connections (8 pts)	Excellent real-world connections	Good connections made	Some connections	Few connections
Writing Quality (4 pts)	Clear, well-organized, error-free	Good writing, minor issues	Adequate writing	Poor writing quality
🔧 Technical Support
Common Issues and Solutions:
Problem: Package installation fails Solution: Restart runtime and try again. Use !pip install --upgrade package_name
Problem: Images don't display properly Solution: Check that matplotlib backend is set correctly. Try %matplotlib inline
Problem: Out of memory errors Solution: Restart runtime, use smaller images, or reduce processing complexity
Problem: Code cells won't run Solution: Check for syntax errors, ensure all imports are successful, restart kernel if needed
Getting Help:
•Email me or contact me on teamcs
•Google Colab Help: Use the "Help" menu in Colab
🎯 Success Tips
Before the Lab:
Review lecture slides on image fundamentals
Ensure you have a stable internet connection
Familiarize yourself with Google Colab interface
Read through the entire lab instructions
During the Lab:
Work systematically through each section
Don't rush - understanding is more important than speed
Experiment with different parameters
Take notes for your reflection journal
Ask questions if you're stuck
After the Lab:
Review your work for completeness
Write your reflection journal while the experience is fresh
Double-check file naming conventions
Submit both files before the deadline
🌟 Going Beyond: Optional Challenges
For students who want to explore further:
Challenge 1: Custom Filter Design
Design your own convolution kernel and explain its effect
Challenge 2: Real Image Analysis
Apply techniques to your own photographs and analyze results
Challenge 3: Performance Comparison
Compare processing times of different methods
Challenge 4: Mobile App Connection
Research how smartphone cameras use these techniques
Challenge 5: AI Tool Analysis
Try Nano Banana or similar tools and analyze the underlying operations
📞 Academic Integrity
•Collaboration: You may discuss concepts with classmates, but all submitted work must be your own
•Code Sharing: Do not share your completed notebook with other students
•External Resources: You may use online resources for learning, but cite any code you adapt
•AI Tools: You may use AI tools for learning assistance, but not for completing the assignment
🎉 Conclusion
This lab bridges the gap between theoretical understanding and practical application. By the end, you'll have hands-on experience with the fundamental operations that power everything from smartphone cameras to advanced AI image processing tools.
Remember: The goal is not just to complete the exercises, but to develop a deep understanding of how image processing works. Take time to experiment, reflect, and connect these concepts to the broader world of computer vision.
Good luck, and enjoy exploring the fascinating world of image processing!
