# V2Ray gRPC Transport

# Historical Context and Standardization

The V2Ray Transport protocol family has evolved over time:

1. **Original V2Ray Transport**  
   - Base transport for WebSocket, HTTP, HTTPUpgrade, gRPC, QUIC
   - Initial framing, multiplexing, and padding model  
   - Project is no longer actively maintained

2. **sing-box branch**  
   - Active reference implementation  
   - Incorporates minor modifications compared to the original V2Ray Transport  
   - Adopted as the standard for this RFS

3. **XTLS branch**  
   - Incorporates minor modifications compared to the original V2Ray Transport  
   - Not adopted as the standard reference for this RFS  

**This RFS standardizes V2Ray Transport as implemented and modified by sing-box.**  