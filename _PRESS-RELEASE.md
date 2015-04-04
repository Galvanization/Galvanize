# Project Name #
Galvanize
<!--
> This material was originally posted [here](http://www.quora.com/What-is-Amazons-approach-to-product-development-and-product-management). It is reproduced here for posterities sake.

There is an approach called "working backwards" that is widely used at Amazon. They work backwards from the customer, rather than starting with an idea for a product and trying to bolt customers onto it. While working backwards can be applied to any specific product decision, using this approach is especially important when developing new products or features.

For new initiatives a product manager typically starts by writing an internal press release announcing the finished product. The target audience for the press release is the new/updated product's customers, which can be retail customers or internal users of a tool or technology. Internal press releases are centered around the customer problem, how current solutions (internal or external) fail, and how the new product will blow away existing solutions.

If the benefits listed don't sound very interesting or exciting to customers, then perhaps they're not (and shouldn't be built). Instead, the product manager should keep iterating on the press release until they've come up with benefits that actually sound like benefits. Iterating on a press release is a lot less expensive than iterating on the product itself (and quicker!).

If the press release is more than a page and a half, it is probably too long. Keep it simple. 3-4 sentences for most paragraphs. Cut out the fat. Don't make it into a spec. You can accompany the press release with a FAQ that answers all of the other business or execution questions so the press release can stay focused on what the customer gets. My rule of thumb is that if the press release is hard to write, then the product is probably going to suck. Keep working at it until the outline for each paragraph flows.

Oh, and I also like to write press-releases in what I call "Oprah-speak" for mainstream consumer products. Imagine you're sitting on Oprah's couch and have just explained the product to her, and then you listen as she explains it to her audience. That's "Oprah-speak", not "Geek-speak".

Once the project moves into development, the press release can be used as a touchstone; a guiding light. The product team can ask themselves, "Are we building what is in the press release?" If they find they're spending time building things that aren't in the press release (overbuilding), they need to ask themselves why. This keeps product development focused on achieving the customer benefits and not building extraneous stuff that takes longer to build, takes resources to maintain, and doesn't provide real customer benefit (at least not enough to warrant inclusion in the press release).
 -->

## Heading ##
  > Name the product in a way the reader (i.e. your target customers) will understand.
  HTTP/2 library for hyper written in Rust

## Sub-Heading ##
  > Describe who the market for the product is and what benefit they get. One sentence only underneath the title.
  Reduce your HTTP request latency by 15% (to 55%) in 15 minutes!

## Summary ##
  > Give a summary of the product and the benefit. Assume the reader will not read anything else so make this paragraph good.
  Galvanize is a HTTP/2 layer that can be used in conjunction with Hyper. Using this layer will move your application to the future and let you be ready for HTTP/2. Benefits include reduced latency, reduced TCP connections, and eliminates HTTP 1.1 workarounds (inline CSS, concatanated files, etc)

## Problem ##
  > Describe the problem your product solves.
  HTTP 1.1 is too slow.

## Solution ##
  > Describe how your product elegantly solves the problem.
  HTTP/2 utilizes binary framing to eliminate request header redundancy, introduces multiplexing bidirectional streams over a single TCP connect per client.

## Quote from You ##
  > A quote from a spokesperson in your company.
  "We've gathered the top engineers in the industry to bring you a bleeding edge library. 100% customer satisfaction guaranteed"

## How to Get Started ##
  > Describe how easy it is to get started.
  OMG. Super easy! First, learn systems programming. Then, "extern crate Galvanize" in your project.

## Customer Quote ##
  > Provide a quote from a hypothetical customer that describes how they experienced the benefit.
  "I thought Node.js was fast, but Galvanized Rust is faster!" - Eli

## Closing and Call to Action ##
  > Wrap it up and give pointers where the reader should go next.
  "You don't wear your clothes from 1998, so why use a protocol that old? Join us in the 21st century with HTTP/2!"
