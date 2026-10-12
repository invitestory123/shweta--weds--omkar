# Client edits from the WhatsApp export

Source: `.private/whatsapp/_chat.txt`, with the four annotated reference images sent on 3 October 2026. The last client feedback in the export is dated 6 October 2026.

| Request | Implementation |
| --- | --- |
| Preserve the client's design and parents' names | Existing portrait artwork retained; both families listed. |
| Doors open into the invitation, without the outward/inward jump | Removed competing CSS doors; one video, matching first-frame poster, natural completion, skip and failure fallback. |
| Hands come together | Plays the supplied hand animation once on entry and retains its final frame. |
| Scratch-to-reveal date | Touch and mouse scratching, keyboard-accessible reveal button, live date announcement. |
| Fuller flower shower | Recurring, bounded petal animation after opening and on date reveal. |
| More motion on ceremony and reception pages, including lights | Lamp glows, twinkles, lake shimmer and animated reception fairy lights. |
| Shweta's name overlaps the floral frame | Explicitly positioned name block inside the frame; type scales with artwork width. |
| Names in Hindi/Devanagari on the blessing page | Corrected groom's name in Devanagari to ओमकार (matching uploaded card photo) and bride's name to श्वेता with Marathi conjunction आणि under ॥ शुभविवाह ॥. |
| Mahadev → Mahadeo | Mahadeo Dagade in HTML and configuration. |
| Vidhi begins 3:15 onwards | 3:15 PM onwards in HTML, configuration and calendar export. |
| Ladies' wedding theme: only Paithani saree | Single Paithani feature showing the first original illustration; other wedding saree types removed from guest-facing content. Reception outfits retained. |
| Venue directions | Maps directions to the address supplied in the chat. |
| Preferred music | Jashn-e-Bahaaraa instrumental integrated as assets/bgm.mp3 with autoplay on entrance and persistent player toggle. |
| Reception time | Updated to 7:30 PM onwards in HTML, JSON configuration, and wedding.ics calendar export. |
| Door opening transition | Eliminated 6-second wait at empty hallway; doors briskly open and transition immediately into the invitation slide with falling petals and music. |
| The update must actually appear | Repeatable source-to-dist build, versioned code/configuration and HTML cache headers. |

The 2026 year and Mangalashtaka at 5:40 PM were retained from the supplied project. Reception updated to 7:30 PM onwards.

