# 09_intro_to_css_frameworks

using tailwind , div class for container section was modify
class flex , was modified to " grid-cols-1(grid coloumns to 1) gap-6 (using a gap of 6) sm:grid-cols-2(small:grid coloumns to 2 ) sm:gap-y-10 (in that small grid , giving a y-exes  gap of 10 ) lg:grid-cols-4" (large grid to colomns of 4 )

h1 (modification)
"max-w-lg(the text width is set to large) text-xl (and the text was was set to extra large) font-semibold( the font was set to semibold) tracking-tight text-[#313131](text color) xl:text-2xl dark:text-white"

styling input (modification)
"px-4 py-2 (padding of y and x exes was set) text-[#313131] bg-white (text color) border rounded-md dark:bg-[#313131](around  the input was set and its color) dark:text-white dark:border-[#313131](border of input was set) focus:border-[#d86943] dark:focus:border-[#d86943] (focus when the input is focused to have a color ) focus:outline-none focus:ring focus:ring-opacity-40 focus:ring-[#d86943]"

button (modification)
w-full px-6 py-2.5 (with of the button is set to full and the padding in y and x exes)
bg-blue-500 (the color of the is set to blue and the size font-weight of 500)
hover:bg-blue-700 (when the button is hovered the color remain blue with the font-weight of 700) focus:bg-blue-700 (when the button is focused the color remain blue with the font-weight of 700) text-white (the text is white) font-italic  focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-opacity-50" ( outline when the button is focus is none and the the ring of 2 with blue around focus and opacity of 50 )

P (modification) (Quick Link and Technologies)
text-[#313131] text-blue-700 ( the text of the paragraph is blue with a font weight of 700 )

a (modification) 
 flex text-green-500 hover:bg-lightgreen-700 hover:underline
 ( it is modified to flex , the text is green and have a weight of 500, when you hover over it the text becames light-green with 700 of font wieght , and it underlies the text)

Flexbox for Mobile Views:
 class="flex flex-col mx-auto mt-6 space-y-3 md:space-y-0 md:flex-row"
 ( the layout of different divices for html to respont and fit by using the flex box flex colomns mx to auto )

 Adjusting Grid Columns
 md:w-1/2
 (giving a span a width of 1/2 make sure the tailwind reponsend to different screen sizes)

hr(modification)
my-6 border-[#d86943] border-green-300 (margin y is set to 6 with a green color and 300 font weight)

Footer Bottom Flex Container(hr)
"flex items-center justify-between" 
(footer is set to flex items are centered and justify in between)

Resize the Browser:
the project is tested for resizing the browser window and observing how the layout adapts to different sizes and everything works well 
 
