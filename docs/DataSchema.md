# Data Schema (Mẫu tham khảo)

## Entity: Table (Bàn)
- TableId: int
- Name: string
- Capacity: int

## Entity: MenuItem (Món ăn)
- ItemId: int
- Name: string
- Price: decimal
- Category: string

## Entity: Order (Đơn đặt)
- OrderId: int
- TableId: int
- Time: datetime
- Status: string

## Entity: OrderDetail (Chi tiết đặt món)
- OrderDetailId: int
- OrderId: int
- ItemId: int
- Quantity: int

## Entity: Staff/User
- UserId: int
- Name: string
- Role: string
- Phone: string

## Entity: Inventory (Kho)
- ItemId: int
- Name: string
- Stock: int
- Unit: string

## Lưu ý
- Có thể bổ sung các trường phù hợp với từng nền tảng (Web/Android/WinForms).
- Hãy mở rộng schema này theo yêu cầu nghiệp vụ và công nghệ.
