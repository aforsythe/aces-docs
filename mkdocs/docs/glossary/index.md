# Terms and Definitions

## A
**Academy Color Encoding Specification (ACES)**
: RGB color encoding for exchange of image data that have not been color rendered, between and throughout production and postproduction, within the Academy Color Encoding System. ACES is specified in SMPTE ST 2065-1.

**ACES RGB relative exposure values**
: Relative responses to light of the ACES Reference Image Capture Device, determined by the integrated spectral responsivities of its color channels and the spectral radiances of scene stimuli.

**ACES unity neutral**
: A triplet of ACES RGB relative exposure values all of which have unity magnitude.

**ACES Metadata File (AMF)**
: Metadata “sidecar” XML-based file that contains information describing a collection of image files color-managed using the Academy Color Encoding System (ACES).

**ACES Encodings**
: Color encoding specifications specified as part of the Academy Color Encoding System, e.g., ACES2065-1, ACEScc, etc.

**ACES File Formats**
: Digital data containers specified as part of the Academy Color Encoding System, e.g., ACES Metadata Files, ACES Image Container (SMPTE ST2065-4), etc.

**ACES Product Partners**
: Companies that integrate ACES concepts and components into their products and/or services.

**ACES System**
: Complete set of components that comprise the Academy Color Encoding System.

**ACES System Release**
: Published ACES System.

**ACES Transforms**
: Color transformations specified as part of the Academy Color Encoding System, e.g., Reference Rendering Transform (RRT), Output Device Transforms (ODT), etc.

**ACES Viewing Transform**
: Combined RRT and ACES Output Device Transform.

## B

## C
**chromatic adaptation**
: process by which the visual mechanism adjusts in response to the radiant energy to which the eyes are exposed.

**chromaticity**
: property of a color stimulus defined by the ratios of each tristimulus value of the color stimulus to their sum.

**Color Transform Langage (CTL)**
: small open-source programming language, consisting of an interpreter and one or more CLT modules, that has been designed to serve as a building block for digital color management systems.

**CTL modules (files)**
: files containing Color Transformation Language code. 
: Note: CTL files are the primary documentation for ACES transforms.

## D
**DateTime**
: (reference: [ISO 8601:2004](https://www.iso.org/standard/40874.html)) timestamp format
: The DateTime is specified in the following form `YYYY-MM-DDThh:mm:ss{offset}` where:
: * `YYYY` indicates the year
: * `MM` indicates the month
: * `DD` indicates the day
: * `T` indicates the start of the required time section 
: * `hh` indicates the hour
: * `mm` indicates the minute
: * `ss` indicates the second
: * `{offset}` time zone offset from UTC
    ??? note 
        All components are required.
    ??? example 
        `2014-11-20T12:24:13-8:00`

## E
**Edit Decision List (EDL)**
: list used in the post-production process of film editing and video editing containing an ordered sequence of reel and timecode data representing where each video clip can be obtained in order to conform to the final cut.

**Extensible Markup Language (XML)**
: a markup language and file format for storing, transmitting, and reconstructing arbitrary data. It defines a set of rules for encoding documents in a format that is both human-readable and machine-readable

## F

## G

## H

## I
**Implementation Transforms**
: ACES System transforms implemented by ACES Product Partners, likely as a Color Look-up Table or as GPU or CPU code.

**Internet Engineering Task Force (IETF)**
: an open standards organization, which develops and promotes voluntary Internet standards, in particular the technical standards that comprise the Internet protocol suite (TCP/IP).

## J

## K

## L
**Look Transform (LMT)** 
**Look Modification Transform** (_deprecated term_)
: ACES transform which applies a global look or other modification to scene-referred image data.
## M
## N
## O
## P
## Q
## R
**Reference Gamut Compression (RGC)**
: ACES LMT which compresses scene-referred image data to within the AP1 gamut.

**Reference Rendering Transform (RRT)**
: Core ACES transform that converts scene-referred image data that conforms to SMPTE ST 2065-1:2012 to output-referred image data.

**RFN**
: technical specification or organizational note published by the Internet Engineering Task Force (IETF)

## S
## T
**TransformIDs**
**Transform Identifiers**
: string identifying the ACES transform.  
    ??? Note 
        Please see the ACES System Versioning Specification for more information on the format to use for TransformIDs.

## U
**Universal(ly) Unique Identifier (UUID)**
: 128-bit label used for information in computer systems published in various standards including ISO/IEC 11578:1996 "Information technology – Open Systems Interconnection – Remote Procedure Call (RPC)"

## V
## W
## X
## Y
## Z



--8<-- "mkdocs/includes/acronyms.md"
