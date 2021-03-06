# Contributing to the WAMP standardization

We are presently starting the process of standardizing WAMP as an IETF standard.

This is via the [hybi working group](), which was formed to create the WebSocket protocol and needs to be re-chartered to standardize WAMP.

There is already an [draft version](https://tools.ietf.org/html/draft-oberstet-hybi-crossbar-wamp) of this online, and a current working version [in this repository](https://github.com/wamp-proto/wamp-proto/)

Before submitting feedback, please

* take a look at the [most current draft document](https://tools.ietf.org/html/draft-oberstet-hybi-crossbar-wamp)
* familiarize yourself with our current [issues list](https://github.com/wamp-proto/wamp-proto/issues) here on GitHub

While the issues list should reflect the current state of discussion, there may be more on the [hybi mailing list](https://mailarchive.ietf.org/arch/search/?email_list=hybi), so [subscribing to this](https://www.ietf.org/mailman/listinfo/hybi) and browsing things there can't hurt.

If you're new to this, you may also want to read the [Tao of the IETF](http://www.ietf.org/tao.html).

Be aware that all contributions to the specification fall under the "NOTE WELL" terms outlined below.

If you have **editorial** suggestions (i.e., those that do not change the meaning of the specification), you can either:

  a) Fork this repository and submit a pull request; this is the lowest
  friction way to get editorial changes in.

  b) Submit a new issue to Github, and mention that you believe it is editorial
  in the issue body. It is not necessary to notify the mailing list for
  editorial issues.

  c) Make comments on individual commits in Github. Note that this feedback is
  processed only with best effort by the editors, so it should only be used for
  quick editorial suggestions or questions.

For non-editorial (i.e., **design**) issues you should create an issue on Github. You **must notify the mailing list** when creating such issues, providing a link to the issue in the message body.


## Working With the Drafts

The draft is written in markdown, with draft-oberstet-hybi-crossbar-wamp-XX.md in the `rfc`folder being the main document.

To keep document length manageable we use file includes, so for actual content see the `text` sub-folder.

For the tooling required to work with this, see the [AUTHORING.md file](AUTHORING.md).


# NOTE WELL

Any submission to the [IETF](http://www.ietf.org/) intended by the Contributor
for publication as all or part of an IETF Internet-Draft or RFC and any
statement made within the context of an IETF activity is considered an "IETF
Contribution". Such statements include oral statements in IETF sessions, as
well as written and electronic communications made at any time or place, which
are addressed to:

 * The IETF plenary session
 * The IESG, or any member thereof on behalf of the IESG
 * Any IETF mailing list, including the IETF list itself, any working group
   or design team list, or any other list functioning under IETF auspices
 * Any IETF working group or portion thereof
 * Any Birds of a Feather (BOF) session
 * The IAB or any member thereof on behalf of the IAB
 * The RFC Editor or the Internet-Drafts function
 * All IETF Contributions are subject to the rules of
   [RFC 5378](http://tools.ietf.org/html/rfc5378) and
   [RFC 3979](http://tools.ietf.org/html/rfc3979)
   (updated by [RFC 4879](http://tools.ietf.org/html/rfc4879)).

Statements made outside of an IETF session, mailing list or other function,
that are clearly not intended to be input to an IETF activity, group or
function, are not IETF Contributions in the context of this notice.

Please consult [RFC 5378](http://tools.ietf.org/html/rfc5378) and [RFC
3979](http://tools.ietf.org/html/rfc3979) for details.

A participant in any IETF activity is deemed to accept all IETF rules of
process, as documented in Best Current Practices RFCs and IESG Statements.

A participant in any IETF activity acknowledges that written, audio and video
records of meetings may be made and may be available to the public.
