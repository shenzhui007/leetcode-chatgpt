class Solution:
    def leastBricks(self, wall: List[List[int]]) -> int:
        edges = {}
        for row in wall:
            edge = 0
            for brick in row[:-1]:
                edge += brick
                edges[edge] = edges.get(edge, 0) + 1
        return len(wall) - max(edges.values(), default=0)
