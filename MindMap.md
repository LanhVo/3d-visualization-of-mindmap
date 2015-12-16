# Mind Map #

Mind maps are diagrams used to represent ideas, tasks, relationships and other similar items in a simpler and effective manner. A mind map is somewhat similar to concept map, however unlike in a concept map where each node has a description a mind map has a single word (idea) in a node. Relevant to this idea various attachments can be made to this node. In a hand drawn mind map this will be basically a picture but in mind map generated in computer this can be any sort of a file, link, note etc.
With contrast to other traditional note taking methods mind maps proves to use 99% of the brain which does not get used in traditional methods. And also since it basically contains a tree structure this can be used for problem solving, search algorithms, various design tasks and other sorts of data representation methods where a large system needs to be visualized efficiently.


# Color Scheme #

## Types of Objects in a Mind Map ##
  1. Main idea – The topic of the mind map.
  1. Main topics – The main categories of the mind map. These are the most adjacent level of main idea.
  1. Sub topics – Objects which are connected to the main topics and subtopics (recursively).

Apart from those objects, following elements are also required to complete the mind map.
  1. Connectors – To connect objects each other.
  1. Call-outs – For comments etc. (Optional).
Color Scheme

### Main Idea ###

> Since there is only one main idea for a mind map there is a specific color can be used. This color should be able to attract the users to it than to other object colors.
### Main Topics ###

> There are several major categories in a mind map. Each of these has to have different colors in order to identify each of them as a different category object. And one other important thing is that the colors which are used for the main topic should not be attractive as the main idea.
### Sub Topics ###

> Subtopics of each main topic should have the same color in order to make it easier analyzing the mind map. Each of these subtopics will have its own subtopics. Therefore each subtopic of a subtopic should have the same color.
### Connections ###

> Changing the color of each connector doesn’t make any sense. Therefore the best thing is to have the same color for all of the connectors and this color should be different from all other colors in mind map.
### Call-outs (Optional) ###

> If the application can contain some call-outs to state the comments and other important data, they all should have the same color and that color should be different from all the colors which are used in the mind map. This color should not make the text inside it hard to read.

# Mindmap Design #
In this application, the mind map is stored in an XML document. Each node in an XML doc-ument represents a node in a mind map. The application will be capable of saving a graphical
representation to an XML document and construct graphical representation out of a valid XML
document. Therefore, generating a mind-map to be displayed in the developed software can be
done in different ways. The software itself will be able to construct such XML. Other software
will be able to output XML documents that is compatible with this and also users will be able
to manually write XML as well.The application allows some user interactions. User can rotate
and Zoom the view. Interactions would be optimized for touch based systems.
The Mindmap application drives using openGL graphics engine. Since our target platform is
mobile based, opengl for embedded Systems(openGl ES) would be used.
Our mind map is based on Spherical layout in order to allow maximum use of the 3D. Also
when arranging the nodes,Veho algorithm is used to avoid overlapping of branches of the
mindmap.Special color schema described in the previous chapter is used to for clear separa-tion of layers and to enhance visibility