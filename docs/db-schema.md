# MongoDB Schemas
- stocks: {ticker: str, timestamp: datetime, price: float, RSI: float, MACD: float}
- news: {article_id: str, text: str, timestamp: datetime}
- xposts: {post_id: str, text: str, timestamp: datetime}
- macro_data: {indicator: str, value: float, timestamp: datetime}
- embeddings: {doc_id: str, embedding: array, collection: str}
- knowledge_graph: {node_id: str, type: str, attributes: dict, edges: list}
