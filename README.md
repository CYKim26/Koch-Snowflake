# Koch-Snowflake

Recursive steps: 
1. Take the line segment
2. Divide the length of the segment by three, giving the length for the new smaller segments
3. With that length draw the new segments, using translate to set the origin to the current triangle and rotate to be able to draw the new segments in the proper relative positions.
  
Base case:
When the length of a line segment is less than or equal to one
